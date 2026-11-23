# Netflix Content Analysis Dashboard

An interactive **Tableau** dashboard exploring Netflix catalog trends across release years, genres, content types (Movies vs. TV Shows), maturity ratings, and global release distribution.

## Dashboard Preview

<img width="794" height="392" alt="image" src="https://github.com/user-attachments/assets/0ca71efa-6797-49ae-8330-4284ecaf4877" />


## Key Visuals & Features

* **Total Releases per Year:** Area chart comparing **Movie** and **TV Show** additions over time, highlighting the sharp growth in catalog releases from the mid-2010s through 2019.
* **Releases by Genre:** Horizontal bar chart ranking top genres by count (such as *Documentaries*, *Stand-Up Comedy*, and international/independent dramas).
* **Movie vs. TV Show Split:** Proportional bubble view showing total counts and share (**4,265 Movies / 68.42%** vs. **1,969 TV Shows** in the current view).
* **Content Rating Breakdown:** Vertical bar chart of show/title counts by maturity rating (such as *TV-MA*, *TV-14*, *TV-PG*, and *R*).
* **Title Description Panel:** Dynamic text pane displaying the plot summary for a selected or filtered title (such as *The 4400*).
* **Releases by Country:** Choropleth map showing release counts by country alongside unlabeled/unknown records.
* **Interactive Filters:** Filter the dashboard dynamically by **Type**, **Title**, and color/count legend controls.

## Design & Layout

* **Theme:** Dark mode (`#000000` canvas) paired with Netflix red (`#E50914` / dark crimson accents) and slate blue (`Movie`) / red (`TV Show`) series encoding.
* **Header:** Replaced the text title with the **NETFLIX** logo centered at the top of the layout.


## Tools Used

* **Tableau Desktop / Tableau Public**
* **Mapbox / OpenStreetMap** (base map tiles)

## How to View / Run

1. Download the `.twb` or `.twbx` workbook from this repository, or open the published view on **Tableau Public** (`[Add Tableau Public URL]`).
2. If opening a `.twb` file locally, connect it to the source dataset file if prompted.
3. Use the **Type** and **Title** filters on the right to explore specific titles, genres, or content types.
