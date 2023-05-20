# CSS Code Explanation

## Font Import

### Code:

```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,500;0,700;1,400&display=swap");
/* ########### container section ############ */
.main {
  height: 100vh;
  background: linear-gradient(rgba(64, 64, 64, 0.8), rgba(71, 71, 71, 0.8)),
    url("assets/pexels-maxyne-barcel-10402282\ 1.png");
  background-size: cover;
  background-position: center;
  padding-top: 2.8rem;
}

.container {
  max-width: 1200px;
  width: 90%;
  margin: auto;
}
/* ######### NAV BAR ########### */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* ... more styles ... */
/* ############ BTN UTILITY CLASS ############ */
.btn {
  display: inline-block;
  padding: 1rem 2.5rem;
  cursor: pointer;
  outline: none;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 700;
  color: #fff;
}

/* ... more styles ... */
/* ############# HERO SECTION ############# */
section[aria-label="hero"] {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 6rem;
}

.hero {
  text-align: center;
}

/* ... more styles ... */
```
