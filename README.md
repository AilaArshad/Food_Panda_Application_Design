# Pizza Menu Android Layout

This XML layout is for an Android pizza menu, displaying images, descriptions, and pricing.

## Features
- **Header Image**: Displays a pizza image at the top.
- **Title Section**: Menu title in bold, colored text.
- **Buttons**: "Popular" and "Favorite" selection buttons.
- **Menu Items**:
  - Name, Ingredients, Price, Popular tag, and Thumbnail image.

## Requirements
- **Drawable Images**: `profile_pizza`, `chiken_tikka`, `chiken_fajita`, `chicago_pizza`, `tandoori_pizza`, `fire`.
- **Strings (res/values/strings.xml)**: `pizza`, `popular`, `favorite`, `pizza1-4`, `ingridents`, `price`, `dis`.
- **Colors**: `@color/black`, `#E91E63`.
- **Custom Drawables**: `@drawable/button_border`, `@drawable/rounded_tag`.

## Usage
1. Copy the XML file to `res/layout`.
2. Ensure required resources exist.
3. Use in an activity with `setContentView(R.layout.your_layout_file);`.
4. Modify text sizes, margins, and colors as needed.

## Screenshot
Below is an image of the rendered layout representing this design.

![image alt](https://github.com/AilaArshad/Instagram/blob/7422282e0041847cab525b36e8b5e802016a8c18/Preview.png)

