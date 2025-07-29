# 🔌 Device Simulator with API Control

This project simulates an IoT environment where devices (e.g., lamps, doors, air conditioners) are controlled via an API and a web interface. The goal is to test your ability to integrate front-end, back-end, business logic, and automated testing.

## 🧠 Challenge

Implement a system that allows:

- Sending sequential commands (e.g., turn on, turn off, set temperature) to simulated devices.
- Updating the current state of each device based on the received commands.
- Validating invalid or conflicting commands.

## ⚙️ Tech Stack

### Backend (BFF)

- Node.js
- TypeScript
- In-memory storage for state simulation

### Frontend

- React
- TypeScript
- API communication via REST

### Testing

- Jest
- Testing Library (end-to-end / integration tests)

## 🚀 Getting Started

1. Install dependencies

```
npm install
```

2. Run the server

```
npm run dev
```

## 🧪 Running Tests

- Unit tests:

```
npm run test
```

- End-to-end tests:

```
npm run test:e2e
```

## 📄 License

MIT
