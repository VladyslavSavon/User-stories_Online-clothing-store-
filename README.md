# User-stories_Online-clothing-store-
User stories for the Online clothing store include 7 user stories that cover 4 User activities: Register User, Log-in User, User's product search using the catalog menu, User's product search using the search field

##

1. As a user, I want to register my profile in the system to buy a product.
    ###
   Acceptance criteria:
   ####
         1. The system must display the username and password fields.
         2. The user can enter a username and password in the corresponding fields.
         3. A password must be between 8 and 50 characters long and can only contain numbers, Latin letters, and punctuation marks.
         4. A username must be between 4 and 20 characters long and can only contain numbers and Latin letters.
         5. The system must ensure that the username is unique and does not duplicate any existing registered usernames,
            maintaining a 100% accuracy rate.
         6. The user can enter a name, surname, phone number, and email address.
         7. A name must be between 1 and 20 characters long and can only contain Latin letters.
         8. A surname must be between 1 and 20 characters long and can only contain Latin letters.
         9. A phone number must be 11 digits long and can only contain numbers.
         10. An email address must contain the symbol “@”.
         11. The system displays the user a message asking the user to check the user's email box.
         12. The system sends a confirmation email to the user's email address entered into the system.
         13. The user must receive the confirmation email at the email address entered into the system.
         14. The confirmation email must ask the user to follow the link to confirm the registration in the system.
         15. The confirmation link must be active and follow back to the system.
         16. The system should start a login session and display a welcome message based on the user's information.
         17. The system must display an error message if the username entered by the user duplicates an existing username.
         18. The system must mark empty fields in red if the user did not fill in all fields.
         19. All fields must be required.
         20. In 90 seconds after sending the confirmation email to the user's email address entered into the system,
             the system must display a message prompting the user to confirm sending another confirmation email.
         21. If the system fails to start a login session after the user confirms registration,
             it displays an error message prompting the user to click the confirmation link again.
   ##
   
2. As a user, I want to log in to the system to buy a product.
   ###
   
   Acceptance criteria:
   ####
          1. The system must display the username and password fields.
          2. The user can enter a username and password in the corresponding fields.
          3. The system must identify the email.
          4. The system must validate the password.
          5. The system must authorize the user.
          6. If the email is identified, the password is validated, and the user is authorized,
             the system must start a login session and display a welcome message based on the user's information.
          7. If the system doesn't identify the user's email, the system must display a message
             to check the correctness of the email and to reenter the email.
          8. If the system doesn't validate the user's password, the system displays a message to check
             the correctness of the password and to reenter the password.
          9. All fields must be required.
          10. The system must mark empty fields in red if the user did not fill in all fields.
          11. If the system fails to start a login session, it displays a message with an error
              asking the user to enter the email and password again.
##

3. As a user, I want to search for a product using the catalog menu to find it.
###

Acceptance criteria:
####
          1. The system must display a start page.
          2. The start page must contain a catalog menu, a search field, personalized recommendations, and discount products.
          3. The user can click on the catalog menu.
          4. After the user clicks on the catalog menu, the system must display the catalog menu page.
          5. The catalog menu page must contain categories of products with no more than 20 categories per page.
          6. The user can click on a category.
          7. The system must display the subcategories page of the selected category.
##

4. As a user, I want to search for a product using the subcategories page to find it.
###

Acceptance criteria:
####
  
          1. The system must display the subcategories page of the selected category.
          2. The subcategories page must contain subcategories of the selected category of products, with no more than 
             20 subcategories per page.
          3. The subcategories page must contain an image and the name of the subcategory.
          4. A subcategory image must have a resolution of at least 300 DPI.
          5. A subcategory name must be limited to a maximum of 25 characters.
          6. The user can click on a selected subcategory of the selected category.
          7. The system must display the product selection page.
##

5. As a user, I want to search for a product using the product selection page.
###

Acceptance criteria:
####

          1. The system must display the product selection page.
          2. The product selection page must contain names and images of products, their short descriptions, and product sorting 
             filters, with no more than 20 products per page.
          3. The name of a product must contain no more than 30 symbols, including gaps.
          4. The product sorting filters must contain at least 8 sorting criteria, depending on the type of product.
          5. The user can select the size to display the names and images of products, with at least two size options available.
          6. Product images must have a resolution of at least 300 DPI.
          7. The short description of a product must be limited to a maximum of 30 characters per point and include no more than 
             three key points.
          8. The user can click on a product name or image.
          9. After the user clicks on a product name or image, the system must display a product page (pg).
##

6. As a user, I want to see a product page to find out more about the selected product.
###

Acceptance criteria:
####

          1. The product page must contain a section (pg1) with all information about the product.
          2. The product page must contain a section (pg2) with only the characteristics of a product.
          3. The product page must contain a section (pg3) with only product feedback.
          4. The product page must contain a section (pg4) for asking about the product.
          5. The product page must contain a section (pg5) for photos and videos of the products.
          6. The product page must contain options for product delivery and options for payment for the product.
          7. The user can click and activate a section (pg1, pg2, pg3, pg4, or pg5) and the button “buy”.
          8. After the user clicks the button “buy”, the system must add the product to the cart
          9. After the user clicks a section (pg1, pg2, pg3, pg4, or pg5), the system displays a corresponding section.
##

7. As a user, I want to search for a product on the website using the search field to find it.
###

Acceptance criteria:
####

          1. The system must display a catalog menu, a search field, personalized recommendations, and discount products.
          2. The user can click on the search field.
          3. After the user clicks on the search field, the system must activate the search field.
          4. The user can enter the name of a desired product in the search field.
          5. The name of the desired product entered in the search field must be limited to a maximum of 200 characters, 
             including gaps.
          6. The user can click the button “Search”.
          7. After the user clicks the button “Search”, the system must display the product selection page with relevant product 
             names from the database based on the user's search query, matching at least three characters of the product name.
          8. If the system doesn't find relevant names of the user's search request in the product database, the system displays 
             a message, that it didn't find the relevant products.
