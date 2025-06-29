# NutriSnap 🥗

NutriSnap is an intelligent nutrition tracker that leverages Generative AI to provide effortless meal logging and deep dietary insights.

---

### Key Features

| Feature                       | Description                                                                                                                                                             |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📸 **AI Food Recognition**    | Instantly log meals by taking a photo. The AI identifies the food, lists the ingredients, names the meal, and estimates its full nutritional profile.                     |
| 🧾 **Label & Receipt Scanner** | Digitize nutrition labels or receipts with your camera. The AI extracts product names, ingredients, and precise nutritional data, handling complex layouts with accuracy. |
| 🏷️ **Dynamic Meal Badges**    | Get at-a-glance insights with AI-generated, color-coded badges (e.g., "High Protein," "High Fat") that summarize the key characteristics of each meal.                   |
| 🧠 **Personalized Insights**  | Receive actionable dietary advice from an AI that analyzes your eating habits over the day, week, or month, identifying trends and areas for improvement.                |
| 📓 **Interactive Meal Journal** | View a clean, compact list of your logged meals. Click any entry to expand a detailed view with a full nutritional breakdown and AI-generated badges.                      |
| 🗑️ **Meal Management**        | Easily manage your journal by deleting entries as needed. All data is securely persisted.                                                                               |

---

### AI Integration

NutriSnap is powered by a suite of specialized AI flows built with Genkit:

| AI Flow | Description |
| :--- | :--- |
| **`recognizeFoodFromImage`** | Visually identifies a meal from a photo, determines its ingredients, and suggests a name. |
| **`readNutritionLabel`** | Performs high-precision OCR on nutrition labels and receipts. It intelligently extracts data, understands layout context, and is trained to omit uncertain information to prevent errors. |
| **`estimateNutritionalValues`**| Calculates a detailed nutritional breakdown (calories, protein, carbs, fat) based on a list of ingredients, whether from food recognition or a receipt. |
| **`generateMealBadges`** | Analyzes the complete nutritional profile of a meal to generate 1-3 insightful, color-coded badges that summarize its health impact. |
| **`generateDietaryInsights`**| Acts as a virtual dietitian, analyzing aggregated meal data over time to provide personalized feedback and recommendations. |
---

### UI & UX Highlights

-   **✨ Clean & Modern Interface:** Built with ShadCN/UI and Tailwind CSS for a professional and intuitive user experience.
-   **📱 Fully Responsive:** The layout adapts seamlessly from desktop to mobile devices.
-   **🚀 Optimized Performance:** Leverages Next.js App Router and Server Components for fast load times and a smooth experience.
-   **🔔 Non-Intrusive Feedback:** Uses toasts for important notifications and errors without disrupting the user flow.
-   **💾 Persistent State:** Meal data is saved locally, ensuring your journal is always up-to-date when you return.



## Showcase
![image](https://github.com/user-attachments/assets/abd41c84-5df5-4256-bc8a-25055d5c2623)
![image](https://github.com/user-attachments/assets/8a8e4faf-da8c-4660-bef5-5c25a7012fa9)
![image](https://github.com/user-attachments/assets/5cf7619e-4a87-42e4-8444-8b0baf1d581e)
![image](https://github.com/user-attachments/assets/85d5485e-943f-420d-a10e-7b11f3724bb3)
![image](https://github.com/user-attachments/assets/7afc0b37-e57e-465b-94e3-444b27c29f40)

