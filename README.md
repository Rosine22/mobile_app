Flutter Recipe App
A simple recipe app built with Flutter that allows users to explore meal categories, view meals under each category, and access detailed information about specific meals, including ingredients and cooking instructions.

Features
Home Screen:
Displays a list of meal categories fetched from an API with category images.
Allows navigation to the Category Screen.

Category Screen:
Shows meals in the selected category in a grid layout with images and titles.
Allows navigation to the Meal Details Screen.

Meal Details Screen:
Displays detailed information about a specific meal, including:

Meal name.
Ingredients and their measurements.
Cooking instructions in a scrollable layout.
API Endpoints
Fetch Categories:

Endpoint: /categories
Fetches a list of meal categories.
Fetch Meals by Category:

Endpoint: /meals?category={categoryName}
Fetches meals under a specific category.
Fetch Meal Details:

Endpoint: /meal?mealId={mealId}
Fetches details of a specific meal, including ingredients and instructions.
Project Structure
bash
Copy code
lib/
├── main.dart                # Entry point of the app
├── api_service.dart         # Manages API calls
├── screens/
│   ├── home_screen.dart     # Home screen with meal categories
│   ├── category_screen.dart # Meals in a category
│   ├── meal_details_screen.dart # Detailed view of a meal
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/flutter-recipe-app.git
cd flutter-recipe-app
Install dependencies:

bash
Copy code
flutter pub get
Run the app:

bash
Copy code
flutter run
Screenshots
(Add relevant screenshots here)

