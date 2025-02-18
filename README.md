# UI Design Challenge: Flight Information Card

## Objective
Design a responsive flight information card that clearly presents complex round-trip flight data while maintaining airline brand consistency and travel usability standards.

## Flight Data Specification

### RoundTrip (CGO → YYZ) (YYZ → CGO)
```json
{
  "flight_number": "CA 2813",
  "aircraft": "333 (Airbus A330-300)",
  "class": "Economy",
  "duration": "12h45m",
  "departure": {
    "time": "04:30",
    "date": "2025-02-28",
    "airport": "CGO (Zhengzhou Xinzheng International Airport)"
  },
  "arrival": {
    "time": "19:45",
    "date": "2025-02-27",
    "note": "+1 day arrival"
  }
}
{
  "flight_number": "CA 4748",
  "aircraft": "333 (Airbus A330-300)",
  "class": "Economy",
  "duration": "11h13m",
  "departure": {
    "time": "10:00",
    "date": "2025-03-08",
    "airport": "YYZ (Toronto Pearson International Airport)"
  },
  "arrival": {
    "time": "03:13",
    "date": "2025-03-09",
    "note": "+1 day arrival"
  }
}
