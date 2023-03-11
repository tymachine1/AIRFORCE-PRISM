# AIRFOCE
<form action="results.html" method="GET" enctype="multipart/form-data">
    <div>
      <label for="name">Name</label>
      <input type="text" name="name" id="name" required>
  </div>
  <div>
    <label for="email">Address</label>
    <input type="email" name="email" id="email" required>
  </div>
  <div>
    <label for="age">ID</label>
    <input type="number" name="age" id="age" min="1" max="200" step="5">
  </div>
  <div>
    <label for="date">NAVY ID</label>
    <input type="date" name="date" id="date" min="1999-01-01">
  </div>
  <div>
    ACC CODE
    <div>
      <label for="MISSILE1"></label>
      <input type="checkbox" name="MISSILE" id="banana">
    </div>
    <div>
      <label for="apple">ATOMIC</label>
      <input type="checkbox" name="ATOMIC" id="apple">
    </div>
  </div>
  <div>
    Gender
    <div>
      <label for="male">Male</label>
      <input type="radio" name="gender" id="male" value="male">
    </div>
    <div>
      <label for="female">Female</label>
      <input type="radio" name="gender" id="female" value="female">
    </div>
  </div>
  <div>
    <label for="eyeColor">TYPE OF WARHEAD</label>
    <select name="eyeColor" id="eyeColor" multiple>
      <option value="MISSILE">MISSILE</option>
      <option label="AIRSTRIKE" value="Red"></option>
    </select>
  </div>
  <div>
    <label for="bio">SEMEN CODE</label>
    <textarea id="ACC NAME" name="bio"></textarea>
  </div>
  <input type="hidden" name="hidden" value="hi">
  <div>
    <label for="file">File</label>
    <input id="file" type="file" name="file">
  </div>
  <div>
    <label for="phone">NAVY ACCSESS CODE</label>
    <input type="tel" name="NAVY ACCSES CODE" id="phone">
  </div>
  <div>
    <label for="url">CITY AND COUNTRY NAME THAT YOU ARE TO NUKE</label>
    <input type="url" name="url" id="url">
  </div>
  <div>
    <label for="color">ACC COLOR</label>
    <input type="color" name="color" id="color">
  </div>
  <div>
    <label>
      Password
      <input type="password" name="password" required>
    </label>
  </div>
  <button type="reset">Reset</button>
  <button type="submit">Submit</button>
</form>
