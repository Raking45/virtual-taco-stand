# Virtual Taco Stand

Welcome to the **Virtual Taco Stand**! This is a modern Angular web application that simulates a taco stand experience, allowing users to browse a menu, place orders, view daily specials, leave feedback, and sign in for a personalized experience.

## Features

- **Home Page:** Learn about the Virtual Taco Stand and its downtown location.
- **Menu:** Browse a variety of handcrafted tacos with detailed descriptions and prices.
- **Order:** Place customized taco orders, including quantity and ingredient preferences.
- **Daily Specials:** View the daily taco special, fetched from a Node.js backend.
- **Feedback:** Submit feedback and view comments from other customers.
- **Authentication:** Sign in to access order functionality (protected by an auth guard).
- **Responsive Design:** Clean, modern, and mobile-friendly layout.

## Tech Stack

- **Frontend:** Angular 18 (standalone components, modern Angular features)
- **Backend:** Node.js (for daily specials API)
- **State Management:** RxJS, Angular services
- **Authentication:** Cookie-based session management
- **Styling:** CSS with Google Fonts

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Angular CLI](https://angular.dev/tools/cli)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/virtual-taco-stand.git
   cd virtual-taco-stand
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the backend server for daily specials:**
   ```sh
   node daily-specials.js
   ```
   The server will run at `http://localhost:3000/api/daily-specials`.

4. **Start the Angular development server:**
   ```sh
   ng serve
   ```
   Navigate to [http://localhost:4200/](http://localhost:4200/) in your browser.

## Running Tests

- **Unit tests:**  
  Run `ng test` to execute unit tests via [Karma](https://karma-runner.github.io).

## Project Structure

- `src/app/` - Angular components and services
- `daily-specials.js` - Node.js backend for daily specials API
- `public/assets/` - Images and static assets

## Usage

- **Sign In:** Use one of the pre-defined user accounts to sign in and place orders.
- **Order Tacos:** Select taco type, quantity, and customizations, then add to your order.
- **View Specials:** Check the "Daily Specials" page for today's featured taco.
- **Leave Feedback:** Submit your feedback and see what others have said.

## Example User Accounts

| Email                        | Password        |
|------------------------------|----------------|
| wizardlywand@hogwarts.com    | Alohomora123   |
| quidditchqueen@hogwarts.com  | Quaxle22       |
| potionmaster@hogwarts.com    | Polyjuice99    |
| mugglemania@hogwarts.com     | Dementor0      |
| spellbinder@hogwarts.com     | Expelliarmus88 |

## License

This project is for educational purposes.

---

*Created with Angular CLI and Node.js. For questions or contributions, please open an issue or pull request.*
