# parkeasy
Help drivers quickly find available parking spaces nearby, saving time, reducing stress, and minimizing traffic congestion.
## Target Users
Drivers in urban areas who need quick and reliable parking solutions, including daily commuters, delivery drivers, ride-share drivers, and tourists.
## Features
### Must Have
- Feature 1: [GPS-based location detection: Automatically detects the user’s current location when the app opens.]
- Feature 2: [Nearby parking spots map: Displays available parking spots around the user in real-time.]
- Feature 3: [Spot details: Shows price, distance, type (disable,delivery…), free/paid status, and hours of operation.]
### Should Have
- Feature 4: [Navigation: Provides turn-by-turn directions to the selected adress.]
- Feature 5: [Real-time updates: Users can see live availability using community reports or sensor data.]
### Could Have
- Feature 6: [Payment integration: Pay for parking directly through the app.]
- Feature 7: [Predictive suggestions: Suggests spots where the user is most likely to find free parking based on past patterns.]
## Data Model
- **ParkingSpot**: id, name, location (lat/lng), price, type (street/garage), hours, availability, sensor_id (optional)
- **User**: id, name, email, payment_info, favorite_spots (list of ParkingSpot IDs)
- **Report**: user_id, parking_spot_id, availability_status, timestamp
## Tech Stack
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Deployed on Vercel
- Payment integration (Stripe/PayPal)
- Google Maps API / Mapbox for maps
- Deployed on Vercel 
## Design
https://www.figma.com/design/Jss3JSaOoot6zjMpGFNTwn/My-app---ParkEasy?node-id=0-1&t=1KerULBusmDmqvtR-1

