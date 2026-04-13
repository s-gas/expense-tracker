# expense-tracker

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

CLI app to track expenses through a JSON file.

## How to run

*Note: to run this project you need to have [Node.js](https://nodejs.org/en) installed.*

Clone this repository:

```bash
git clone https://github.com/s-gas/expense-tracker.git
```

Change to the project directory:

```bash
cd expense-tracker
```

Install the required packages:

```bash
npm install
```

Run the program:

```bash
./expense-tracker.js <command> [arguments]
```

### Available commands

- Add an expense:
```bash
add --description "description" --amount <amount>
```

- Update an expense:
```bash
update --id  --description "new description"
```

- Delete an expense:
```bash
delete --id <id>
```

- List all expenses:
```bash
list
```

- Show total expenses:
```bash
summary
```

- Show total expenses for a specific month:
```bash
summary --month <month>
```

*Note: All commands need to be prefixed with `./expense-tracker.js`*
