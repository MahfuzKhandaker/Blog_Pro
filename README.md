# Blog_Pro
Django Blog Project

## 1. Custom User Model
Highly recommended to set up a custom user model when starting a new Django project. Without it, you will need to create another model (like UserProfile) and link it to the Django user model with a OneToOneField if you want to add new fields to the user model.

