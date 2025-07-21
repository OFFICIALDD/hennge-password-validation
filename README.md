Password Validation Challenge – React & Vue (TypeScript)
This project includes two implementations of a password validation form using:

React + TypeScript

Vue 3 + TypeScript

Both implementations follow the same validation rules, are built with Vite, and maintain consistency in UI and logic.

Getting Started
React Version
bash
Copy
Edit
cd challenge/react
npm install
npm run dev
Visit: http://localhost:5173

Vue Version
bash
Copy
Edit
cd challenge/vue
npm install
npm run dev
Visit: http://localhost:5173

Password Validation Rules
The following rules are enforced in both versions:

Minimum 8 characters

At least one uppercase letter (A–Z)

At least one lowercase letter (a–z)

At least one digit (0–9)

At least one special character (!@#$%^&*() etc.)

Sample Test Cases
Username	Password	Valid	Reason
testuser	Test123!	Yes	Meets all criteria
user123	test123!	No	Missing uppercase letter
admin	Admin12	No	Missing special character
guest	Guest!	No	Less than 8 characters

Features
Identical functionality in both frameworks

Real-time validation with helpful error messages

Clean, organized code using best practices

Shared validation logic

Fully typed with TypeScript

Project Structure
bash
Copy
Edit
challenge/
├── react/
│   ├── src/
│   │   ├── components/
│   │   ├── utils/validation.ts
│   │   └── constants.ts
│   └── package.json
├── vue/
│   ├── src/
│   │   ├── components/
│   │   ├── utils/validation.ts
│   │   └── constants.ts
│   └── package.json
└── README.md
Development Commands
Each project includes the following commands:

bash
Copy
Edit
npm run dev        # Start the local development server
npm run build      # Build for production
npm run preview    # Preview the production build
npm run validate   # Run TypeScript type checks
npm run lint       # Lint the source code
npm run format     # Format code using Prettier
Package Info
Final zip: password-validation-enhanced.zip

node_modules not included

Fully documented

Production-ready
