## Employee Directory Web App

A simple web application to manage and display employee information. Users can view, add, and delete employees, with all data managed via a JSON file and dynamic UI updates.

---

**Features**

- View a list of employees with quick selection
- Display detailed information for each employee
- Add new employees (with age validation: minimum 18 years)
- Delete employees from the list
- Responsive and clean UI

---

**Project Structure**

| File         | Purpose                                                |
|--------------|--------------------------------------------------------|
| `index.html` | Main HTML structure for the Employee Directory         |
| `style.css`  | Styles for layout, modals, and responsive design       |
| `data.json`  | Employee data in JSON format                          |
| `script.js`  | Handles UI logic: rendering, adding, deleting employees|

---

**How to Run**

1. Place all files (`index.html`, `style.css`, `data.json`, `script.js`, and `gfg.png`) in the same directory.
2. Open `index.html` in your browser.

---

**Usage**

- **View Employees:** Click any name in the left panel to see details.
- **Add Employee:** Click the “Add a new Employee” button, fill the form, and submit.
- **Delete Employee:** Click the ❌ next to an employee's name.

---

**Customization**

- Update `data.json` to change initial employee data.
- Employee images use `gfg.png` by default; you can provide a different image URL when adding a new employee.

---

**Notes**

- Email validation is minimal; ensure correct format when adding employees.
- Age is auto-calculated from the date of birth.

---

**Sample Employee Data Format**

```json
{
  "id": 1001,
  "imageUrl": "gfg.png",
  "firstName": "Thomas",
  "lastName": "Leannon",
  "email": "Thomas.Leannon@gfg.com",
  "contactNumber": "4121091095",
  "age": 43,
  "dob": "26/08/1979",
  "salary": 1,
  "address": "Address1"
}
```

---

**License**

Free to use and modify for personal or educational projects.
