# Release Notes Version 0.1

**GitHub Issues** https://github.com/CMDT/TimeSeriesDataCapture/issues

**Single Page Web App** https://timeseriesdatacapture-spwa.herokuapp.com/#!/home/

## Version 0.1 Implemented Features

### Searching

#### Search Bar
- Runs can be searched either by date or time

#### Search Results
- A single run can be viewed
- Multiple runs can be viewed

#### Search URL
- The search query is stored within the URL

---
 
### Viewing

#### Graph
- The graph can be panned
- The graph can be zoomed
- Active Trend can be offset
- X-axis can be locked
- Y-axis can be locked
- Offset Line

#### Annotations
- Annotation can be viewed
- Annotation can be added
- Annotation can be deleted
- Annotation can be repositioned
- Annotation description can be edited

#### Tags
- Tags can be viewed
- Tags can be added
- Tags can be deleted

#### Column Tag Panel
- Column Tag Panel can be switched to display either tags or columns
- Column visibility can be switched
- Active Trend can be changed

#### URL State
- Zoom level, offset, visible columns & active trend all stored within the UR

## Version 0.1 Needed Features

### Searching

#### Search Buttons
- Exporting selected runs to CSV format
- Deleting specific runs

---

### Viewing

#### Graph
- Touchscreen controls

#### Column Tag Panel
- Persistant tag changes
- Trend line colour pallete

### Importing
- All of import

### Authentication
- OneDrive Authentication
- Auth0 Authentication


## Example Tests
[Website](https://timeseriesdatacapture-spwa.herokuapp.com/#!/home/)
### Searching

- **Step 1** : Search for runs by time, 10:38:25, two results will show.
- **Step 2** : Copy and paste the URL into a sperate tab, the same two results will show
- **Step 3** : Select multiple results by selecting each checkbox
- **Step 4** : To view runs either click the View button or click a specific result

*Example [search]( https://timeseriesdatacapture-spwa.herokuapp.com/#!/home/?query=%252010:38:25) for 10:38:25, warning open in new tab* 

### Viewing
#### Graph Control
- **Step 1** : Using the scroll wheel zoom the graph in and out
- **Step 2** : Holding shift and dragging the graph will pan about
- **Step 3** : Clicking and dragging the graph will offset the active trend (*The red line indicates active trend offset*)
- **Step 4** : To lock an axis click either lock button (*try panning the graph*)
- **Step 5** : Copy and paste the URL into a sperate tab

*Example [graph view](https://timeseriesdatacapture-spwa.herokuapp.com/#!/view?runs=2B497C4DAFF48A9C!178&columns=2B497C4DAFF48A9C!178:RTH%2B2B497C4DAFF48A9C!178:T(Environment)&viewVector=%7B%22k%22:0.6,%22x%22:45.41,%22y%22:153.79%7D&offsetVector=%7B%22x%22:569.07,%22y%22:-129.01%7D&active=2B497C4DAFF48A9C!178%2BRTH), warning open in new tab*

#### Column Tag Panel Control
- **Step 1** : On the Column Tag Panel, toggle the visibilty of multiple columns by selecting each checkbox
- **Step 2** : Click on a column to set the active trend
- **Step 3** : Click on the second tab to view the second run columns
- **Step 4** : Click the column switch to view run tags
- **Step 5** : Click the pencil icon to edit tags
- **Step 6** : To confirm changes click the confirm button

#### Annotation Control
- **Step 1** : Click plus sign to add new annotation
- **Step 2** : Click downwards arrow to reposition annotation
- **Step 3** : Click and hold on black downward arrow then drag to reposition
- **Step 4** : Click stop, black square, to confirm new postion
- **Step 5** : Click pencil to edit annotation description
- **Step 6** : Click confirm to confirm annotation descitpion
- **Step 7** : To close annoation panel click off it
- **Step 8** : Click annotation to view
- **Step 9** : To delete annotation click the delete button


## Add GitHub Issue
- **Step 1** : Navigate to [TimeSeriesDataCapture Repositry](https://github.com/CMDT/TimeSeriesDataCapture/issues)
- **Step 2** : Naviagate to the Issues Tab
- **Step 3** : Click the green New Issue button
- **Step 4** : Add Issue title and description
- **Step 5** : Label the issue by clicking the Label gear button (on the left)
- **Step 6** : Click the green Submit new issue button

*Please don't forget to label issues with the version number (version_0_1) and if it is a bug or an enhancement. If it is a bug please leave steps to reproduce it, example [issue](https://github.com/CMDT/TimeSeriesDataCapture/issues/3)*
 
---

*[attribution](https://github.com/CMDT/TimeSeriesDataCapture/blob/master/Documents/attribution.md)*
