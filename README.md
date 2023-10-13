# Blog_Pro
Django Blog Project

## 1. Custom User Model
Highly recommended to set up a custom user model when starting a new Django project. Without it, you will need to create another model (like UserProfile) and link it to the Django user model with a OneToOneField if you want to add new fields to the user model.

## 2. Posts app
Now added Post apps in project. Craete model with Category, Tag, Post, and Comment-reply.

## 3. Write on view.py as per need
Functions -
-- Post create
-- post list with lazy load pagination
-- Search result: Post search with query
-- Post detail with dynamic like, love and with comment-reply activity
-- Post by category and post by tag, and more utility set up
## 4. Create custom forms.py and mixins.py files
crispy form and markdown editor set up


