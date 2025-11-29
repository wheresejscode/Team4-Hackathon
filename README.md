# Team4-Hackathon
Sustainable Travel Route Optimizer

A web application that optimizes travel routes for sustainability, minimizing carbon emissions by comparing routes based on mode of transport (e.g., driving, public transit, biking) and real-time factors like traffic and distance.

Features
- **Route Generation**: Calculates multiple route options using external APIs.
- **Emission Calculations**: Estimates CO2 emissions for each route.
- **Recommendations**: Suggests the most sustainable route based on emissions and user preferences.
- **Interactive Maps**: Visualize routes with comparisons on a map.
- **Multimodal Support**: Supports driving, walking, cycling, and public transport.

 Tech Stack
- **Backend**: Node.js, Express, Axios (for API calls).
- **Frontend**: React, Leaflet (for maps).
- **APIs**: OpenRouteService (routing), optional: Google Maps API (for alternatives).
- **Testing**: Jest (backend), React Testing Library (frontend).

Prerequisites
- Node.js (v16+)
- npm or yarn
- Git



sustainable-travel-route-optimizer/
├── backend/                          
│   ├── src/
│   │   ├── controllers/              
│   │   ├── services/                 
│   │   ├── models/                   
│   │   ├── utils/                    
│   │   └── app.js                    
│   ├── tests/                        
│   ├── package.json                  
│   ├── .env.example                  
│   └── README.md                     
├── frontend/                         
│   ├── src/
│   │   ├── components/               
│   │   ├── pages/                    
│   │   ├── services/                 
│   │   ├── utils/                    
│   │   └── App.js                   
│   ├── public/                       
│   ├── tests/                        
│   ├── package.json                  
│   └── README.md                     
├── .gitignore                        
├── docker-compose.yml                
├── LICENSE                           
└── README.md                         
