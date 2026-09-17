# 🎵 Music Database SQL Analysis

A SQL-based analysis of a music store database (Chinook-style), exploring artists, albums, tracks, genres, customers, and invoices to answer common business questions using core SQL techniques — filtering, aggregation, joins, and conditional logic.

## 📁 Dataset

The dataset consists of 8 related tables imported as CSV files into MySQL:

| Table | Description |
|---|---|
| `artist` | Musical artists |
| `album` | Albums, linked to their artist |
| `track` | Individual tracks, linked to album, genre, and media type |
| `genre` | Music genres |
| `media_type` | File/media format types |
| `customer` | Customer records |
| `invoice` | Purchase invoices, linked to customers |
| `invoice_line` | Line items per invoice, linked to tracks |

## 🛠️ Tools Used

- **MySQL** — database setup and querying
- CSV import (tables and data loaded directly via import, no manual `CREATE TABLE` step)

## ❓ Business Questions Answered

- What are all the tracks, and which ones are priced above/below certain thresholds?
- Which customers are from India, and what countries do customers come from overall?
- What are the total number of tracks, customers, and invoices?
- What is the average, minimum, and maximum track price?
- How many customers are in each country, and how many tracks are in each genre?
- Which artists have more than one album?
- What are the track names along with their album and artist names?
- Which customers have the highest total spending?
- Which artists have no albums (and vice versa)?
- How can tracks, invoices, and customers be categorized (e.g., Premium/Regular, Domestic/International, High Value/Normal)?
- What is the most expensive track, the top genre by track count, and the highest-spending customer?

## 📊 Key Insights

- **Highest-spending customer:** Rahul Sharma, with a total spend of **$6.93**
- **Most expensive track:** "Hello" by Adele, priced at **$1.29**
- **Top genre by track count:** Rock leads with **6 tracks**, followed by Pop (4), then Hip-Hop, Indian, and Classical (2 each)
- **Customer base:** 10 customers total — 7 from India, 2 from the USA, 1 from the UK
- **Catalog size:** 16 tracks total, averaging **$1.04** per track
- **Total revenue:** **$39.92** across all invoices, averaging **$2.66** per invoice
- **Artist catalog:** all 8 artists (The Beatles, Adele, Eminem, Arijit Singh, Coldplay, Taylor Swift, Linkin Park, A.R. Rahman) each have exactly 1 album and 2 tracks
- **Most frequent buyers:** a three-way tie between Karan Jain, Rohit Kumar, and Vikas Yadav, each with 2 invoices.




