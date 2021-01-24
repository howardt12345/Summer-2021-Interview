## Repository: 

```
https://github.com/howardt12345/outstem-waste-wizard
```

## Deployed App URL: 

```
https://outstem-2021.howardt12345.com/
```

## Run Instructions

1. Cloning the repo and navigating to folder:

   ```sh
   git clone https://github.com/howardt12345/outstem-waste-wizard.git
   cd outstem-waste-wizard
   ```

2. Installing dependencies with npm:

   ```sh
   npm install
   ```

3. Starting the development server:

   ```sh
   npm start
   ```

   The site should now be running at `http://localhost:3000`.

## Additional Information

### Technical Requirements Met

1. App will be accessible using a browser ✓
2. You can use any framework, library you like ✓
3. Data will come from the dataset mentioned above. ✓
4. Each result will list at least the following information ✓
     - Item name 
     - Item description
     - The bin it belongs in and a picture of such bin (URLs to all pictures can be found in the Data & Assets section)
5. There will be at most 5 results displayed at a time for any query, have a load more button that will display the next 5 results ✓
6. The search will happen as the user types ✓
7. Items in the search result can be added to the “waste room” ✓
8. The “add to waste room” button should be disabled if the item is already in the waste room ✓
9. The waste room should have 4 sections, items will be automatically added to their matching section: ✓
     - Regular trash & curbside pickup
     - Recycling
     - Organics & Yard waste
     - Hazardous Waste
10. When an item is in the waste room their name will be displayed. ✓
11. The app will be optimized for mobile devices like smartphones and tablets. ✓

### Extra Requirements Met

-	Frank thinks it would be nice to have debouncing for the search box since his computer is not very fast ✓
-	Frank is a visual head and would like to see some slick animations on the app (loading, moving items and removing items) ✓