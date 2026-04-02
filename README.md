# Version Control, Testing & Deployment Project

## Overview
This project demonstrates the use of version control using Git, along with automated testing using Jest.

---

## Technologies Used
- Git
- Node.js
- Jest

---

## Project Structure
- math.js → Contains function logic  
- math.test.js → Contains test cases  

---

## Testing

Run tests using:
```bash
npm test

test('adds 2 + 3 = 5', () => {
  expect(add(2, 3)).toBe(5);
});
