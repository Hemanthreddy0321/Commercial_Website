# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## HTML
```
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
          <div class="bg-container d-flex flex-column justify-content-end">
              <div class="tourism-card">
                  <h1 class="main-heading">Tourism</h1>
                  <p class="paragraph">Plan your trip.</p>
                  <button class="button">Get Started</button>
              </div>
          </div>
      </body>




    <div class="favourite-places-bg-container">
      <h1 class="favourite-places-heading">Favourite Places</h1>

      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Taj Mahal</h1>
          <p class="favourite-place-card-description">
            If there was just one symbol to represent all of India, it would be
            the Taj Mahal
          </p>
        </div>
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
          class="favourite-place-card-image"
        />
      </div>

      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Golden Temple</h1>
          <p class="favourite-place-card-description">
            Amritsar is world-famous for the beautiful and highly revered Golden
            Temple
          </p>
        </div>
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png"
          class="favourite-place-card-image"
        />
      </div>

      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Mysore Palace</h1>
          <p class="favourite-place-card-description">
            The Mysore Palace is a historical palace and the royal residence at
            Mysore .
          </p>
        </div>
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png"
          class="favourite-place-card-image"
        />
      </div>

      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
          <p class="favourite-place-card-description">
            Varanasi Temple is most famous Hindu temples dedicated to Lord Shiva
          </p>
        </div>
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png"
          class="favourite-place-card-image"
        />
      </div>
    </div>
  </body>
</html>
```
## CSS
```

.bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
    height: 100vh;
    background-size: cover;
}

.tourism-card {
    text-align: center;
    background-color: white;
    padding: 5px;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
}

.main-heading {
    font-family: "Roboto";
}

.paragraph {
    font-family: "Roboto";
}

.button {
    color: white;
    background-color: #25b1cc;
    width: 138px;
    height: 36px;
    border-width: 0px;
    border-radius: 20px;
}


.favourite-places-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
  height: 100vh;
  background-size: cover;
}

.favourite-places-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
  padding: 24px;
}

.favourite-place-card-container {
  background-color: white;
  border-radius: 8px;
  padding: 16px;
  margin: 15px;
}

.favourite-place-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}

.favourite-place-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}

.favourite-place-card-image {
  width: 80px;
  height: 100px;
}
```
## OUTPUT

![WhatsApp Image 2025-03-16 at 22 38 20_a8c56c8d](https://github.com/user-attachments/assets/a5b7184a-b76e-4e1d-a689-e3561722fe9d)

![WhatsApp Image 2025-03-16 at 22 37 28_16ed0813](https://github.com/user-attachments/assets/2dd3c75d-0251-4ccf-9ea3-6a4d0544120c)



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
