#Project structure
/perfect_hair
├── .husky/                  
├── node_modules/
├── public/                  
└── src/                     
    ├── api/                 
    │   ├── authService.js   
    │   └── bookingService.js
    ├── assets/              
    │   ├── design/          
    │   └── images/          
    ├── components/          
    │   ├── Cards/           
    │   │   └── MasterCard.jsx 
    │   ├── Form/            
    │   │   └── InputField.jsx
    │   ├── UI/              
    │   │   └── Button.jsx
    │   └── Header.jsx       
    ├── hooks/               
    │   └── useAuth.js       
    ├── pages/               
    │   ├── Auth/            
    │   │   ├── LoginPage.jsx
    │   │   └── RegisterPage.jsx
    │   ├── Booking/         
    │   │   ├── MasterSelect.jsx
    │   │   └── TimeSelect.jsx
    │   ├── Profile/         
    │   │   ├── ClientProfile.jsx
    │   │   └── EmployeeProfile.jsx
    │   └── HomePage.jsx     
    ├── styles/              
    │   └── global.css
    ├── utils/               
    │   └── validationRules.js
    ├── main.jsx             
    └── App.jsx              