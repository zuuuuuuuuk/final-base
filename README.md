 variant-1
 
practical tasks:

1. create module named profile. inside profile module, generate component with same name. use lazy loading for this module. (5pts)
2. (signals) generate service and use it for api calls (https://restaurant.stepprojects.ge/swagger/index.html), get all products and cart products. show cart length on home component (computed signal). (7pts)
3. inside home template, use @for() (angular 16 version for *ngFor) cycle to render products. create fake log in logic and let user see products only if credentials are correct (generate fake token and store it in localStorage. use route guard and if log in fails, navigate to home component)(13pts)
4. create logic for adding product to cart and logic for removing product from cart.(5pts)

theoretical part:

1. Explain what lazy loading is in Angular and why it is useful. Give an example from your project (ProfileModule). (3pts)
answer here: 


2. Explain the purpose of a route guard. How does your fake login logic prevent unauthorized users from seeing products? (2pts)
answer here:

3. Explain how signals work in Angular 21. Why did you use a computed signal for cart length instead of just storing a number in the service? (5pts) 
answer here: