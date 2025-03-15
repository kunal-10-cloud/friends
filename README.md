# Friends App

![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Devise](https://img.shields.io/badge/Devise-Auth-blue?style=for-the-badge)

A modern, user-friendly contact management application built with Ruby on Rails. The Friends App helps you keep track of your friends' contact information with an elegant and professional user interface.

## ✨ Features

- **User Authentication**: Secure login and registration system
- **Contact Management**: Add, view, edit, and delete friends
- **Profile Cards**: Beautiful profile cards for each friend with visual identifiers 
- **Real-time Search**: Instantly search your contacts by name, email, or phone number
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **User-specific Contacts**: Each user can only see and manage their own contacts

## 🚀 Technologies

- **Ruby on Rails**: Web application framework
- **Bootstrap 5**: Frontend component library for responsive design
- **Devise**: Authentication solution
- **SQLite/PostgreSQL**: Database
- **Bootstrap Icons**: Icon library
- **Custom CSS**: Enhanced styling with modern UI components
- **Turbo/Hotwire**: Modern navigation without full page reloads

## 📥 Installation

1. **Clone the repository**

```bash
git clone https://your-repository-url/friends.git
cd friends
```

2. **Install dependencies**

```bash
bundle install
```

3. **Setup the database**

```bash
rails db:create
rails db:migrate
```

4. **Start the server**

```bash
rails server
```

5. **Visit the application**

Open your browser and navigate to `http://localhost:3000`

## 📋 Usage

### Registration/Login

- Create a new account or login using the navigation menu
- Authentication is required to access the friends management features

### Managing Friends

- **View Friends**: All your friends are displayed in a clean, organized list
- **Add a Friend**: Click "Add New Friend" to create a new contact with:
  - First and last name
  - Email address
  - Phone number (optional)
  - Twitter handle (optional)
- **Search**: Use the search bar to filter your contacts in real-time
- **View Details**: Click on a friend to see their complete profile
- **Edit/Delete**: Easily update or remove contacts as needed


## 🔒 Authentication

This application uses Devise for handling user authentication. Each user can only view and manage their own friends, ensuring privacy and data separation.

## 📱 Responsive Design

The Friends App is fully responsive and works on:

- 💻 Desktop computers
- 📱 Mobile phones
- 📟 Tablets

The UI automatically adjusts to provide the best experience on any device.

## 🔄 Future Improvements

Planned features for future releases:

- Friend grouping/categorization
- Birthday reminders
- Import/export contacts
- Social media integration
- Dark mode
- Advanced filtering and sorting options

## 🌐 Deployment

The application can be deployed to:

- Heroku
- Railway
- Render
- Any platform supporting Ruby on Rails

## 🙋‍♂️ Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

Aditya Bijalwan - Initial work

## 🙏 Acknowledgments

- Ruby on Rails community
- Bootstrap team
- Devise contributors
- All open-source packages used in this project
