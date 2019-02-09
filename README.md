# Project Title

Virtual Tourist Version 2 

## Getting Started

Virtual Tourist is an application that allows the user to navigate the world from home.It shows a map of the world and the user will be able to put a pin in any place to view its fantastic pictures and places. 

### Prerequisites

To compile the app you need to have swfit 4 or above and it was built in xcode 10.1

### Implementation

The App has the following view controllers:

MapController: shows the map and allows the user to drop a pin in any location. locations are saved in the desk using CoreData

CollectionController:Used to download the photos for the selected location. 

The application uses Flicker API to fetch the photos. The photos are saved and stored using CoreData.

