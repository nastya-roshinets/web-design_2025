#Project structure
/perfect_hair
├── .husky/                  
├── node_modules/
├── public/                  
src/
    ├── api/
    │   ├── authService.js
    │   ├── bookingService.js
    │   └── staffService.js       
    ├── components/
    │   ├── Cards/
    │   │   ├── MasterCard.jsx
    │   │   ├── EmployeeCard.jsx   
    │   │   └── AppointmentCard.jsx
    │   ├── Form/
    │   │   ├── InputField.jsx
    │   │   ├── Select.jsx         
    │   │   └── ImageUpload.jsx    
    │   └── UI/
    │       ├── Button.jsx
    │       ├── Header.jsx
    │       └── Footer.jsx         
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
    │   ├── HomePage.jsx
    │   └── StaffPage.jsx
    ├── styles/              
    │   └── global.css
    ├── utils/               
    │   └── validationRules.js
    ├── main.jsx             
    └── App.jsx              