# React Pagination Task

## Objective
Implement a paginated list in React.js using the provided mock data.

---

## Mock Data

```js
export const users = [
  { id: 1, name: 'Alice Johnson', email: 'alice.johnson@example.com' },
  { id: 2, name: 'Bob Smith', email: 'bob.smith@example.com' },
  { id: 3, name: 'Charlie Davis', email: 'charlie.davis@example.com' },
  { id: 4, name: 'Diana Evans', email: 'diana.evans@example.com' },
  { id: 5, name: 'Ethan Brown', email: 'ethan.brown@example.com' },
  { id: 6, name: 'Fiona Lewis', email: 'fiona.lewis@example.com' },
  { id: 7, name: 'George Hall', email: 'george.hall@example.com' },
  { id: 8, name: 'Hannah Lee', email: 'hannah.lee@example.com' },
  { id: 9, name: 'Ian Clark', email: 'ian.clark@example.com' },
  { id: 10, name: 'Jane King', email: 'jane.king@example.com' },
  { id: 11, name: 'Kyle Moore', email: 'kyle.moore@example.com' },
  { id: 12, name: 'Laura Scott', email: 'laura.scott@example.com' },
  { id: 13, name: 'Mike Adams', email: 'mike.adams@example.com' },
  { id: 14, name: 'Nina Walker', email: 'nina.walker@example.com' },
  { id: 15, name: 'Oscar Hill', email: 'oscar.hill@example.com' },
  { id: 16, name: 'Paula Green', email: 'paula.green@example.com' },
  { id: 17, name: 'Quinn Harris', email: 'quinn.harris@example.com' },
  { id: 18, name: 'Rachel Lewis', email: 'rachel.lewis@example.com' },
  { id: 19, name: 'Steve Martinez', email: 'steve.martinez@example.com' },
  { id: 20, name: 'Tina Nelson', email: 'tina.nelson@example.com' },
  { id: 21, name: 'Uma Patel', email: 'uma.patel@example.com' },
  { id: 22, name: 'Victor Reed', email: 'victor.reed@example.com' },
  { id: 23, name: 'Wendy Young', email: 'wendy.young@example.com' },
  { id: 24, name: 'Xander Brooks', email: 'xander.brooks@example.com' },
  { id: 25, name: 'Yara Adams', email: 'yara.adams@example.com' },
  { id: 26, name: 'Zane Parker', email: 'zane.parker@example.com' },
];
```

## Task Instructions

### Basic Task
- Implement a paginated list in React.js displaying the **name** and **email** of each user.
- Display **5 users per page**.
- Show **Next** and **Previous** buttons to navigate pages.
- Optionally, display the **current page number** and **total pages**.

### Requirements
- Ensure the pagination logic works for any size of the list.
- Even if we later change the `users` array to a larger or smaller dataset, the pagination should adapt.

### Optional Advanced Tasks
- Add a **page size selector** (e.g., 5, 10, 20) that dynamically changes the number of users per page.
- Disable the **Previous** button when on the first page, and the **Next** button when on the last page.
- **Bonus:** Make the pagination accessible (ARIA labels, keyboard navigation).

### Code Structure
- Use **functional React components**.
- Maintain the **current page state** using `useState`.
- Use the **users** data provided (do not fetch data from an API).

---