## 1. Facts 

- The college has shared equipment. 

- Equipment includes laptops, cameras and projectors. 

- Bookings currently use email and spreadsheets. 

- Double bookings have occurred. 

- Staff spend time checking bookings manually. 

- Equipment is not always returned when expected. 

## 2. Assumptions 

- Students and staff may both need to make bookings. 

- Some equipment may require approval. 

- Users will need to know equipment availability. 

- Staff will need to manage bookings. 

## 3. Unknowns 

- Who is authorised to book? 

- How long can equipment be booked? 

- Is approval required? 

- What happens when equipment is returned late? 

- What information must be recorded? 

- Who manages the booking process? 

## 4. Stakeholders 

| Stakeholder | Need / Concern | 

| Students | Availability and straightforward booking | 

| Lecturers | Access to equipment for teaching | 

| Equipment staff | Managing bookings and returns | 

| Management | Efficient resource use | 

| IT staff | System support | 

## 5. Goals 

- Reduce double bookings. 

- Improve visibility of equipment availability. 

- Reduce manual booking administration. 

## 6. Scope 

### In scope 

- Equipment availability 

- Equipment booking 

- Booking management 

- Equipment return information 

### Out of scope / not yet established 

- Mobile application 

- Specific database technology 

- Payment system 

## 7. Candidate Requirements 

### Functional 

FR1. The system shall allow an authorised user to request 

equipment for a specified date and time. 

FR2. The system shall allow an authorised user to view 

equipment availability. 

FR3. The system shall prevent overlapping confirmed bookings 

for the same equipment. 

FR4. The system shall allow authorised staff to manage 

equipment bookings. 

### Non-functional 

NFR1. The system should support accessible use. 

NFR2. The system shall restrict booking-management functions 

to authorised users. 

## 8. Requirement Surgery 

### R1 — Easy to use 

Weak because "easy" is subjective and difficult to test. 

Possible improvement: 

A first-time student user should be able to complete a standard 

equipment booking without assistance. 

### R2 — Secure 

Weak because "secure" does not identify what must be protected 

or from whom. 

Possible improvement: 

The system shall restrict equipment-management functions to 

authorised staff. 

Reflection 

1. Facts ≠ assumptions 

Do not turn an assumption into a requirement just because it sounds reasonable. 

2. Unknowns are useful 

An unknown tells us what we need to investigate next. 

3. Stakeholders are more than users 

People who influence, support, manage, regulate or are affected by the system can all be stakeholders. 

4. Requirements are not solutions 

“We need a mobile app” is a proposed solution. 
“Users need convenient access to booking information” describes a need. 

5. Requirements improve through iteration 

Version 1 is supposed to be incomplete. 

The overall journey you want is: 

Problem → Stakeholders → Unknowns → Elicitation → Analysis → Requirements → Models → Validation → Change 

Rather than: Problem → “Let's build an app.” 
