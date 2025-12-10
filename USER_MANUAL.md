# Recipe Manager - User Manual

## Welcome to Recipe Manager! 🍳

Your personal digital cookbook for organizing, searching, and managing your favorite recipes. This comprehensive guide will help you make the most of your Recipe Manager app.

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [Creating Your Account](#creating-your-account)
3. [Home Screen Overview](#home-screen-overview)
4. [Adding Recipes](#adding-recipes)
5. [Searching Recipes](#searching-recipes)
6. [Managing Your Recipes](#managing-your-recipes)
7. [Viewing Recipe Details](#viewing-recipe-details)
8. [Tips & Tricks](#tips--tricks)
9. [Troubleshooting](#troubleshooting)
10. [FAQs](#faqs)

---

## Getting Started

### First Launch

When you first open Recipe Manager, you'll see the login screen. If you're new to the app, you'll need to create an account.

### System Requirements

- **iOS**: iOS 13.0 or later
- **Android**: Android 5.0 or later
- **Internet Connection**: Required for syncing recipes

---

## Creating Your Account

### Sign Up

1. **Tap** "Don't have an account? Sign Up" at the bottom of the login screen
2. **Enter** your email address
   - Must be a valid email format (e.g., yourname@example.com)
3. **Create** a password
   - Minimum 6 characters required
   - Use a strong, unique password
4. **Confirm** your password by typing it again
5. **Tap** "Sign Up"

✅ **Success!** You'll see a confirmation message and be automatically signed in.

### Sign In

1. **Enter** your registered email address
2. **Enter** your password
3. **Tap** "Sign In"

🔒 **Security Note**: Your password is encrypted and never stored in plain text.

---

## Home Screen Overview

Your home screen is your recipe dashboard. Here's what you'll see:

### Header Section
- **Welcome Message**: Personalized greeting with your email
- **Logout Button**: Red icon in the top-right corner to sign out

### Recipe Statistics

Two colorful cards showing:
- **Total Recipes**: Your entire recipe collection count
- **This Week**: Recipes you added in the last 7 days

### Quick Actions

Three convenient buttons for common tasks:

1. **➕ Add Recipe** (Blue)
   - Opens the form to create a new recipe
   - Fastest way to add recipes

2. **🔍 Search** (Purple)
   - Jump directly to the search screen
   - Find recipes by title or keywords

3. **📝 All Recipes** (Orange)
   - View and manage your entire collection
   - Access swipe-to-delete features

### Recent Recipes

Displays your 3 most recently added recipes:
- **Tap any recipe** to view its full details
- Shows recipe name and creation date
- Empty if you haven't added recipes yet

### Pull to Refresh

**Swipe down** on the home screen to refresh your recipe count and recent recipes.

---

## Adding Recipes

### Opening the Add Recipe Screen

**Three ways to add a recipe:**
1. Tap "Add Recipe" on the home screen
2. Use the quick action button
3. Tap "Add Recipe" from the empty state in Manage screen

### Filling Out the Recipe Form

#### 1. Recipe Title (Required)
- **Field**: "Recipe Title"
- **Character Limit**: 30 characters maximum
- **Example**: "Chocolate Chip Cookies"
- **Tip**: Keep it short and descriptive

#### 2. Recipe Steps (Required)
- **Field**: "Recipe Steps"
- **Character Limit**: Unlimited
- **Format**: One step per line
- **Example**:
  ```
  1. Preheat oven to 350°F
  2. Mix flour, sugar, and butter
  3. Add chocolate chips
  4. Bake for 12-15 minutes
  ```
- **Tip**: Press Enter/Return after each step for better formatting

#### 3. Keywords (Optional)
- **Field**: "Keywords"
- **Character Limit**: 30 characters maximum
- **Format**: Comma-separated words
- **Example**: "dessert, baking, chocolate"
- **Purpose**: Makes your recipe easier to find in search
- **Tip**: Use tags like cuisine type, meal type, or main ingredients

### Character Counters

Watch the character counters below Title and Keywords fields:
- Shows "X/30" format
- Turns red when limit reached
- Prevents typing beyond limit

### Creating the Recipe

1. **Fill in** all required fields (Title and Steps)
2. **Add** optional keywords if desired
3. **Tap** the blue "Create Recipe" button

✅ **Success!** You'll see:
- A success toast notification
- Automatic navigation to your new recipe's detail page

### Canceling

**Tap** the back button or swipe down to cancel and return to the previous screen without saving.

---

## Searching Recipes

The Search screen helps you find recipes quickly using titles or keywords.

### Accessing Search

1. Tap the **Search** tab at the bottom
2. Or tap **Search** quick action from home screen

### How to Search

1. **Tap** the search bar (auto-focused on load)
2. **Type** your search term
   - Search works on recipe titles
   - Search works on keywords
3. **Wait** for instant results (0.3 seconds delay)
4. **View** the result count below the search bar

### Search Features

#### Real-Time Results
- Results appear as you type
- No need to press Enter or Search button
- Debounced for performance (slight delay)

#### Case-Insensitive
- "CHOCOLATE" finds "chocolate"
- "Pasta" finds "pasta"

#### Partial Matching
- "choc" finds "Chocolate Chip Cookies"
- "dess" finds recipes with "dessert" keyword

### Search Results

**Each result shows:**
- Recipe title
- Number of steps
- Keywords (if any)
- Creation date

**Tap any result** to view the full recipe details.

### No Results?

If no recipes match your search:
- You'll see a "No Results" message
- Suggestions for trying different keywords
- Clear the search to try again

### Clearing Search

**Tap the X button** (clear icon) in the search bar to:
- Empty the search field
- Reset results
- Start a new search

---

## Managing Your Recipes

The Manage screen displays your complete recipe collection with powerful management features.

### Accessing Manage

Tap the **Manage** tab at the bottom navigation bar.

### Recipe List

All your recipes are displayed as cards showing:
- Recipe title
- Number of steps
- Keywords
- Creation date

### Viewing a Recipe

**Tap any recipe card** to open its detail page.

### Swipe to Delete Feature

Remove recipes with a simple swipe gesture:

1. **Swipe left** on any recipe card
2. The card slides left revealing "Delete"
3. **Continue swiping** past the threshold
4. A confirmation dialog appears

⚠️ **Confirmation Dialog**
- **Title**: "Delete Recipe"
- **Message**: Shows which recipe will be deleted
- **Cancel**: Closes dialog without deleting
- **Delete**: Permanently removes the recipe

### Pull to Refresh

**Swipe down** on the recipe list to refresh and sync your recipes.

### Empty State

If you have no recipes yet:
- You'll see a friendly "No Recipes Yet" message
- An "Add Recipe" button to get started
- Instructions to build your collection

---

## Viewing Recipe Details

The Recipe Detail screen shows complete information about a selected recipe.

### Accessing Recipe Details

**Three ways:**
1. Tap a recipe from Recent Recipes on home screen
2. Tap a search result
3. Tap a recipe from Manage screen
4. Automatically shown after creating a new recipe

### Recipe Information Display

#### Header
- **Recipe Title**: Large, prominent display
- **Creation Date**: When the recipe was added

#### Keywords Section
- Displayed as colorful badges/chips
- Only appears if keywords were added
- Blue background with rounded corners

#### Steps Section
- **Header**: "Steps" with bullet icon
- **Format**: Numbered list (1, 2, 3...)
- **Display**: Each step on its own line
- Easy to follow while cooking

### Actions

#### Delete Recipe Button
- **Location**: Bottom of the screen
- **Color**: Red (destructive action)
- **Icon**: Trash can
- **Action**: Opens confirmation dialog

**Deletion Process:**
1. Tap "Delete Recipe" button
2. Confirmation dialog appears
3. Choose "Cancel" or "Delete"
4. If deleted, returns to previous screen
5. Success message confirms deletion

### Pull to Refresh

**Swipe down** to refresh the recipe details and sync any changes.

### Navigation

**Tap the back arrow** (top-left) to return to the previous screen.

---

## Tips & Tricks

### Recipe Organization

#### Use Descriptive Titles
✅ Good: "Grandma's Apple Pie"  
❌ Avoid: "Pie 1"

#### Write Clear Steps
✅ Good: "Preheat oven to 350°F for 10 minutes"  
❌ Avoid: "Heat oven"

#### Add Helpful Keywords
Examples:
- **Meal Type**: breakfast, lunch, dinner, snack
- **Cuisine**: italian, mexican, chinese, indian
- **Dietary**: vegetarian, vegan, gluten-free
- **Difficulty**: easy, medium, hard
- **Season**: summer, winter, holiday
- **Main Ingredient**: chicken, beef, pasta, rice

### Search Strategies

#### Quick Searches
- Use single keywords: "chocolate", "pasta", "chicken"
- Search by meal type: "breakfast", "dessert"
- Find by cuisine: "italian", "mexican"

#### Finding Forgotten Recipes
- Try ingredient names: "tomato", "basil"
- Search cooking methods: "baked", "grilled"
- Use season keywords: "summer", "holiday"

### Workflow Optimization

#### Weekend Batch Entry
- Add multiple recipes at once
- Copy recipes from cookbooks or websites
- Build your collection during downtime

#### Quick Access Favorites
- Add star emoji (⭐) to favorite recipe titles
- Search for "⭐" to find favorites quickly
- Example: "⭐ Best Chocolate Cake"

#### Meal Planning
- Add day keywords: "monday", "weeknight"
- Tag prep time: "quick", "slow-cook"
- Mark family favorites: "kids", "crowd-pleaser"

---

## Troubleshooting

### Common Issues & Solutions

#### Can't Sign In

**Problem**: "Sign In Failed" error  
**Solutions**:
- ✅ Verify email address is correct
- ✅ Check password (case-sensitive)
- ✅ Ensure internet connection is active
- ✅ Try "Sign Up" if you haven't created an account

#### Recipes Not Appearing

**Problem**: Recipe list is empty  
**Solutions**:
- ✅ Pull down to refresh the screen
- ✅ Check your internet connection
- ✅ Sign out and sign back in
- ✅ Verify you're using the same account

#### Search Not Working

**Problem**: No results or search not responding  
**Solutions**:
- ✅ Wait 0.3 seconds after typing
- ✅ Try simpler search terms
- ✅ Check spelling of search query
- ✅ Clear search and try again
- ✅ Ensure recipes have relevant keywords

#### App Running Slowly

**Problem**: Lag or slow response  
**Solutions**:
- ✅ Close and reopen the app
- ✅ Restart your device
- ✅ Check internet speed
- ✅ Clear device storage space
- ✅ Update to latest app version

#### Can't Delete Recipe

**Problem**: Swipe gesture not working  
**Solutions**:
- ✅ Swipe left (not right)
- ✅ Swipe firmly past halfway
- ✅ Try tapping recipe to view details, then use Delete button
- ✅ Restart the app

#### Recipe Won't Save

**Problem**: "Create Recipe" button doesn't work  
**Solutions**:
- ✅ Check Title field is filled (required)
- ✅ Check Steps field is filled (required)
- ✅ Verify Title is under 30 characters
- ✅ Verify Keywords is under 30 characters
- ✅ Check internet connection

---

## FAQs

### General Questions

**Q: Is Recipe Manager free?**  
A: Yes! Recipe Manager is completely free to use with unlimited recipes.

**Q: Do I need an account?**  
A: Yes, an account ensures your recipes are securely stored and synced across devices.

**Q: Can I use Recipe Manager offline?**  
A: No, an internet connection is required to sync recipes with the cloud database.

**Q: How many recipes can I store?**  
A: There's no limit! Store as many recipes as you like.

**Q: Can I share recipes with others?**  
A: Currently, recipes are private to your account. Sharing features may be added in the future.

### Account & Security

**Q: How secure is my data?**  
A: Very secure! Your data is protected with:
- Encrypted passwords
- Row-level security (you only see your recipes)
- Secure cloud storage with Supabase

**Q: Can I change my password?**  
A: Currently, password reset must be done through Supabase. Contact support for assistance.

**Q: What if I forget my password?**  
A: Contact support with your registered email address for password reset assistance.

**Q: Can I delete my account?**  
A: Contact support to request account deletion. All your recipes will be permanently removed.

### Recipe Management

**Q: Can I edit recipes after creating them?**  
A: The edit feature is planned for a future update. Currently, you can delete and recreate recipes.

**Q: Can I add photos to recipes?**  
A: Photo support is planned for a future version of the app.

**Q: Can I categorize recipes?**  
A: Use the Keywords field to add categories like "breakfast", "dessert", "italian", etc.

**Q: Can I export recipes?**  
A: Recipe export is planned for a future update.

**Q: What if I accidentally delete a recipe?**  
A: Deletions are permanent and cannot be undone. A confirmation dialog helps prevent accidents.

**Q: Can I print recipes?**  
A: Direct printing is not currently available but planned for future versions.

### Search & Organization

**Q: Can I filter recipes?**  
A: Use the search feature with keywords like "dessert" or "quick" to filter recipes.

**Q: Can I sort recipes?**  
A: Recipes are automatically sorted by creation date (newest first).

**Q: Can I create recipe folders?**  
A: Not currently, but you can use keywords as "virtual folders" (e.g., "favorites", "holiday").

**Q: Why doesn't search find my recipe?**  
A: Search only looks at titles and keywords. Make sure your recipe has relevant keywords added.

### Technical Questions

**Q: Which devices are supported?**  
A: Recipe Manager works on:
- iOS devices (iPhone, iPad)
- Android phones and tablets
- Web browsers (limited support)

**Q: Do recipes sync between devices?**  
A: Yes! Sign in with the same account on multiple devices to access your recipes anywhere.

**Q: How much storage does the app use?**  
A: Minimal! Recipes are stored in the cloud, not on your device.

**Q: Can I use it on my tablet?**  
A: Yes! The app is fully responsive and works great on tablets.

---

## Getting Help

### Need More Assistance?

If you encounter issues not covered in this manual:

1. **Check Documentation**
   - README.md for technical details
   - SETUP.md for installation help
   - TESTING_CHECKLIST.md for feature verification

2. **Contact Support**
   - Email: support@recipemanager.app (example)
   - Include: Your account email, device type, and issue description
   - Screenshots help diagnose issues faster

3. **Community Resources**
   - Expo Forums: https://forums.expo.dev/
   - Supabase Discord: https://discord.supabase.com/
   - React Native Community: https://reactnative.dev/community/overview

---

## App Version Information

**Current Version**: 1.0.0  
**Last Updated**: December 2025  
**Platform**: iOS, Android, Web

---

## Quick Reference Card

### Essential Actions

| Action | How To |
|--------|--------|
| **Sign Up** | Tap "Sign Up" → Enter email & password → Confirm |
| **Sign In** | Enter credentials → Tap "Sign In" |
| **Add Recipe** | Tap "Add Recipe" → Fill form → Tap "Create" |
| **Search** | Tap Search tab → Type in search bar |
| **View Recipe** | Tap any recipe card |
| **Delete Recipe** | Swipe left OR open recipe → Tap "Delete Recipe" |
| **Refresh** | Pull down on any list screen |
| **Sign Out** | Tap logout icon on home screen |

### Keyboard Shortcuts (Web)

- **Tab**: Move between form fields
- **Enter**: Submit forms
- **Esc**: Close modals
- **Ctrl/Cmd + S**: Save (when applicable)

---

## Best Practices

### For Best Experience

✅ **Do:**
- Add keywords to all recipes for easier searching
- Write clear, numbered steps
- Use descriptive titles
- Regularly back up important recipes (screenshot or copy)
- Keep your app updated to the latest version
- Maintain a stable internet connection

❌ **Avoid:**
- Using special characters in titles
- Exceeding character limits
- Deleting recipes impulsively (deletions are permanent)
- Sharing your password with others
- Using public Wi-Fi for account access

---

## Future Features Preview

### Coming Soon

We're constantly improving Recipe Manager! Planned features include:

- 📸 **Recipe Photos**: Upload images with your recipes
- ✏️ **Edit Recipes**: Update recipes after creation
- 📁 **Categories**: Organize recipes into custom categories
- ⭐ **Favorites**: Mark and filter favorite recipes
- 🍽️ **Meal Planning**: Weekly meal planner integration
- 📤 **Recipe Sharing**: Share recipes with friends and family
- 📊 **Cooking Stats**: Track your cooking habits
- 🌙 **Dark Mode**: Reduce eye strain with dark theme
- 🗣️ **Voice Input**: Dictate recipes while cooking
- 🛒 **Shopping Lists**: Auto-generate ingredient lists

Stay tuned for updates!

---

## Conclusion

Thank you for choosing Recipe Manager! We hope this app helps you organize your recipes and inspires you to cook amazing meals.

**Happy Cooking! 🍳**

---

*This user manual is for Recipe Manager version 1.0.0. Features and instructions may change in future updates.*
