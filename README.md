# Solidus Ecommerce Project Template

This repository serves as a template for creating new ecommerce stores 
using Solidus, a powerful open-source ecommerce framework built on top 
of Ruby on Rails. By using this template, you can quickly set up a new 
Solidus-based project with a pre-configured structure, saving you time 
and effort when creating new ecommerce stores.

## Getting Started

Follow these steps to create a new Solidus-based ecommerce store using this template:

## Prerequisites

Make sure you have the following software installed on your system:

* Ruby (recommended version 3.2.2)
* Ruby on Rails (recommended version 7.0.7.1)
* PostgreSQL (for database)
* Git

## Creating a New Solidus Ecommerce Store

1. Clone this Template Repository:

```
https://github.com/HydraSoul2000/SolidusStore
```

2. Navigate to the Project Directory:

```
cd your-ecommerce-store
```

3. Install Dependencies:

```
bundle install
```

4. Set Up the Database:

```
rails db:create
rails db:migrate
```

5. Load Sample Data (Optional):

```
rails db:seed
```

6. Start the Server:

```
rails server
```
The application should now be accessible at http://localhost:3000.

7. Access the Admin Interface:

To access the Solidus admin interface, go to http://localhost:3000/admin in your browser. You can log in using the default admin credentials:

* Email: spree@example.com
* Password: spree123

8. Customize and Build Your Store:

You can now start customizing your ecommerce store according to your 
needs. Modify the views, layouts, and styles to match your branding. 
You can also extend the functionality by adding new Solidus extensions 
or writing custom code.

## Pushing to Git

Once you have set up and customized your Solidus-based ecommerce store, 
you can push your project to a Git repository to have a ready-to-use 
template for future projects.

1. Initialize a New Git Repository:

```
git init
git add .
git commit -m "Initial commit"
```

2. Create a Remote Repository:

Create a new repository on your preferred Git hosting 
platform (e.g., GitHub, GitLab, Bitbucket).

3. Add the Remote Repository:

```
git remote add origin <repository-url>
```

4. Push to the Remote Repository:

```
git push -u origin master
```

Now you have your Solidus ecommerce project template stored 
on Git. In the future, whenever you need to create a new 
ecommerce store with Solidus, you can simply clone this 
repository and start customizing it.

## Additional Resources

- [Solidus Documentation](https://guides.solidus.io/)
- [Ruby on Rails Guides](https://guides.rubyonrails.org/)

Feel free to reach out if you have any questions or need 
assistance with setting up or customizing your Solidus 
ecommerce store based on this template. Happy selling!