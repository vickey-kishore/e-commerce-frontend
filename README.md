# Steps done to create this project

    - npm create vite@latest
    - give project name
    - give package name
    - select a framework from list of options
    - select a variant (language) from list of options
    - cd to created project
    - npm install
    - npm run dev

# Component Flow

[BrowseAllRooms] - RoomListing --> Room --> RoomCard, RoomPaginator, RoomFilter

[/] - Home --> MainHeader, Parallax, HotelService, RoomCarousel, RoomSearch

[/book-room/:roomId] - Checkout --> BookingForm --> BookingSummary

    - BookingSuccess --> Header

# GitHub Page

    1. npm install gh-pages
    2. add homePage, predeploy, deploy in package.json
