# EmployWise - User Management System

## Features

- 🔐 Secure authentication system
- 👥 User listing with pagination
- 🔍 Real-time search and filtering
- ✏️ User editing functionality
- 🗑️ User deletion
- 📱 Responsive design for all devices
- 🎨 Modern Material-UI components
- ✨ Smooth animations and transitions

## Tech Stack

- React.js
- Material-UI (MUI)
- React Router
- Axios for API calls
- Framer Motion for animations
- Context API for state management

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/employ_wise.git
cd employ_wise
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

```
src/
├── components/
│   ├── Login.js
│   ├── UsersList.js
│   └── EditUser.js
├── context/
│   └── AuthContext.js
├── App.js
└── index.js
```

## API Integration

This project uses the [ReqRes](https://reqres.in/) API for demonstration purposes. It's a free mock API that simulates a real REST API.

### API Endpoints Used

- Login: `POST https://reqres.in/api/login`
- Get Users: `GET https://reqres.in/api/users`
- Get User: `GET https://reqres.in/api/users/:id`
- Update User: `PUT https://reqres.in/api/users/:id`
- Delete User: `DELETE https://reqres.in/api/users/:id`

## Important Notes

1. **Authentication**
   - The application uses token-based authentication
   - Tokens are stored in localStorage
   - Protected routes require authentication

2. **API Limitations**
   - ReqRes is a mock API, so changes won't persist
   - Pagination is limited to 2 pages
   - User updates are simulated

3. **Test Credentials**
   - Email: eve.holt@reqres.in
   - Password: cityslicka

## Features in Detail

### User Management
- View all users with pagination
- Search users by name or email
- Filter users by different criteria
- Edit user details
- Delete users

### Search and Filter
- Real-time search across all user fields
- Filter by name or email
- Case-insensitive search
- Maintains pagination state while filtering

### UI/UX
- Responsive design for all screen sizes
- Loading states and error handling
- Smooth animations and transitions
- Modern Material-UI components
- Intuitive navigation

## Development Considerations

1. **State Management**
   - Uses React Context for authentication state
   - Local state for user data and UI states
   - Efficient state updates for better performance

2. **Error Handling**
   - Comprehensive error handling for API calls
   - User-friendly error messages
   - Graceful fallbacks

3. **Security**
   - Protected routes
   - Token-based authentication
   - Secure API calls

4. **Performance**
   - Optimized re-renders
   - Efficient data filtering
   - Smooth animations

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Material-UI](https://mui.com/) for the component library
- [ReqRes](https://reqres.in/) for the mock API
- [Framer Motion](https://www.framer.com/motion/) for animations
