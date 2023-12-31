# DigitalTolk Test

### 💫 Some `good things` about the code

#### 👉 Code is `well-structured`
#### 👉 Code is well-factored making it `reusable`
#### 👉 Code is well documented using `comments` & `Documentation`
#### 👉 Code is following the `Repository Pattern`
#### 👉 `BookingController` seems follow the `modular design`
#### 👉 Code promotes `Dependency Injection` principle 
#### 👉 Code follows a consistent `Naming` convention
#### 👉 Code seems to follow `Error Handling`
#### 👉 Code also follow custom `Response Hanlding` using `response()` method

<br>

### ⚠️ Some bad things about the code


#### Although the code is very well-structured, but there are few things that would have made it outstanding code, let's talk about those things.

#### 👉 Code inside `BookingController` does not seems to follow validation on the `$request`
#### 👉 `$request->all()` has often been used inside code, well one should avoid this practice as it risks system security only retrieve data you want to use!
#### 👉 Lack of `middleware` usage
#### 👉 `Mass Assignment Risk` as the code uses `$request->all()`
#### 👉 No use of `Auth` Facade inside directly accessing `__authenticatedUser`
#### 👉 One should use Database Transactions to make code fault-tolerant
#### 👉 Code Duplication
#### 👉 Some of the return statements are very ambiguous cannot understand if they are used on purpose
#### 👉 Error handling could be improved using more `descriptive messages`
#### 👉 Some parts require `documentation or comments`
#### 👉 `Raw SQL` is used, use `Eloquent` for better `security` & `maintainability`
#### 👉 Should follow `abstraction` across the code
#### 👉 Large Methods i.e. `store` are used
#### 👉 A lot of conditional statements are used but no proper commenting

<br>

### I know there might be more issues I missed, but these were I think the most important one!





