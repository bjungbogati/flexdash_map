library(leaflet)


loc <- readr::read_csv("loc.csv")


leaflet() %>%
addTiles() %>%
addMarkers(loc$lng, loc$lat, popup=loc$name)


