```html
<!-- HTML Forms and Inputs -->
<form action="/submit" method="post">
  <!-- Collects user data and sends it to the server -->

  <!-- Text input -->
  <label for="name">Name:</label>
  <input
    type="text"
    id="name"
    name="name"
    placeholder="Enter your name"
    required />

  <!-- Email input -->
  <label for="email">Email:</label>
  <input
    type="email"
    id="email"
    name="email"
    placeholder="Enter your email"
    required />

  <!-- Password input -->
  <label for="password">Password:</label>
  <input
    type="password"
    id="password"
    name="password"
    placeholder="Enter your password"
    required />

  <!-- Number input -->
  <label for="age">Age:</label>
  <input type="number" id="age" name="age" min="18" max="100" />

  <!-- Radio buttons -->
  <label>Gender:</label>
  <input type="radio" id="male" name="gender" value="male" /> Male
  <input type="radio" id="female" name="gender" value="female" /> Female

  <!-- Checkbox -->
  <label for="subscription">Subscribe to newsletter:</label>
  <input type="checkbox" id="subscription" name="subscription" />

  <!-- Dropdown -->
  <label for="country">Country:</label>
  <select id="country" name="country">
    <option value="india">India</option>
    <option value="usa">USA</option>
    <option value="uk">UK</option>
  </select>

  <!-- Textarea -->
  <label for="bio">Bio:</label>
  <textarea
    id="bio"
    name="bio"
    rows="4"
    cols="50"
    placeholder="Tell us about yourself"></textarea>

  <!-- Submit button -->
  <button type="submit">Submit</button>
</form>

<!-- Attributes of Form Elements -->
<form
  action="/submit"
  method="post"
  target="_blank"
  novalidate
  enctype="multipart/form-data">
  <!-- 'action': Specifies where data is sent -->
  <!-- 'method': Defines HTTP method (e.g., POST/GET) -->
  <!-- 'target': Opens response in a new tab/window -->
  <!-- 'novalidate': Disables validation -->
  <!-- 'enctype': For file uploads -->

  <label for="username">Username:</label>
  <input
    type="text"
    id="username"
    name="username"
    required
    placeholder="Enter your username" />

  <label for="file">Upload File:</label>
  <input type="file" id="file" name="file" />

  <button type="submit">Submit</button>
</form>
```
