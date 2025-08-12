## Authentication page

form Fields & Validation Rules

Field	Required?	Validation Rule	Error Message Example
Full Name	✅	Must be at least 2 characters, letters and spaces only	"Please enter a valid full name (letters only)."
Email	✅	Must match standard email regex (e.g., user@example.com)	"Please enter a valid email address."
Phone Number	✅	Digits only, 10–15 digits allowed	"Please enter a valid phone number (10–15 digits)."
Age	✅	Must be a number and ≥ 18	"You must be at least 18 years old to register."
Event Category	✅	Must choose one from dropdown	"Please select an event category."
Additional Notes	❌	Optional, max length 300 characters	—
Terms Checkbox	✅	Must be checked before submission	"You must agree to the terms and conditions."
