# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Soft red: hsl(7, 99%, 70%)
- Yellow: hsl(51, 100%, 49%)
- Dark desaturated cyan (graphic design text):
hsl(167, 40%,24%)
- Dark blue (photography text): hsl(198, 62%, 26%)
- Dark moderate cyan (footer): hsl(168, 34%, 41%)

### Neutral

- Very dark desaturated blue: hsl(212, 27%, 19%)
- Very dark grayish blue: hsl(213, 9%, 39%)
- Dark grayish blue: hsl(232, 10%, 55%)
- Grayish blue: hsl(210, 4%, 67%)
- White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 18px

### Font

- Family: [Barlow](https://fonts.google.com/specimen/Barlow)
- Weights: 600
- Family: [Fraunces](https://fonts.google.com/specimen/Fraunces)
- Weights: 700, 900

## Icons

We provide the required social icons. But, if you prefer, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com)
- [IcoMoon](https://icomoon.io)
- [Ionicons](https://ionicons.com)

.container-fluid {
  /* padding-left: 0;
  padding-right: 0; */
}

.col-lg-4 {
  /* padding: 3%; */
}

.row {
  margin: 0;
}

.row>* {
  /* margin-right: 0;
  margin-left: 0;
  padding-left: 0;
  padding-right: 0; */
}

/* NAVIGATION SECTION */
.header-image {
  width: 100%;
  height: 100%;
  position: absolute;
  z-index: -1;
  object-fit: cover;
}

.arrow-image {
  margin-left: 740px;
  margin-top: 120px;
}

.navigation-container {
  padding: 3% 7%;
}

.navbar-brand {
  font-weight: bold;
}

.nav-item {
  margin: 0 10px;
}

.nav-btn {
  border-top-left-radius: 100px;
  border-top-right-radius: 100px;
  border-bottom-right-radius: 100px;
  border-bottom-left-radius: 100px;
  border-style: none;
  padding: 4%;
  width: 40%;
  background-color: white;
  font-family: 'Fraunces', serif;
  font-weight: bold;
}

/* ABOUT SECTION */
#about {
  margin-top: 295px;
}

/* Transform sub-section */
.transform {
  padding-right: 0;

}

.egg-image {
  width: 100%;
  height: 100%;

}


.trannsform-egg {
  background-color: hsl(51, 100%, 49%);
}

.transform-heading {
  font-family: 'Fraunces', serif;
  font-weight: 900;
  font-size: 3rem;
  width: 65%;
  letter-spacing: px;
}

.transform-items {
  /* margin-left: 50px; */
  padding: 10%;
}

.transform-text-2 {
  font-family: 'Barlow', sans-serif;
  margin-top: -100px;
  font-size: 1.3rem;
  color: hsl(232, 10%, 55%);
  width: 90%;
}

.transform-btn {
  text-decoration-color: hsl(51, 100%, 80%);
  background-color: hsl(51, 170%, 95%);
  border-top-left-radius: 100px;
  border-top-right-radius: 100px;
  border-bottom-right-radius: 100px;
  border-bottom-left-radius: 100px;
  font-family: 'Fraunces', serif;
  font-weight: bold;
  border-style: none;
  color: black;
  padding: 1%;
  margin-left: 75px;
}

/* Stand-out Subsection */
.cup-image {
  width: 100%;
}

.stand-out-items {
  padding: 10%;
}

.stand-out-heading {
  width: 80%;
}

.stand-out-text1 {
  width:
  font-family: 'Barlow', sans-serif;
  margin-top: -100px;
  font-size: 1.3rem;
  color: hsl(232, 10%, 55%);
  width: 90%;
}

.stand-out-button {
  background-color: hsl(7, 150%, 95%);
  text-decoration-color: hsl(7, 99%, 88%);
  border-top-left-radius: 100px;
  border-top-right-radius: 100px;
  border-bottom-right-radius: 100px;
  border-bottom-left-radius: 100px;
  border-style: none;
  color: black;
  padding: 1%;
  margin-left: 75px;
}

/* Graphic-design Sub-section */
.grape-image {
  position: relative;
  width: 100%;
  height: 106%;
  z-index: -1;
}

.graphic-heading {
  margin-top: -200px;
  margin-left: 225px;
  color: hsl(167, 40%, 24%);
}

.graphic-content {
  text-align: center;
  margin-left: 190px;
  width: 51%;
  margin-top: 20px;
  color: hsl(167, 40%, 24%);
}

.orange-image {
  position: relative;
  z-index: -1;
  width: 100%;
  height: 106%;
}

.orange-heading {
  margin-top: -200px;
  margin-left: 250px;
  color:  hsl(198, 62%, 26%);
}

.orange-content {
  margin-top: 20px;
  text-align: center;
  width: 50%;
  margin-left: 190px;
  color:  hsl(198, 62%, 26%);
}

/* TESTIMONIAL SECTION */

#testimonials {
  margin-top: 25px;
  margin-bottom: 50px;
}

.testimonial-main-heading {
  padding: 3% 2% 2%;
  text-align: center;
  margin-left: 270px;
  margin-top: 80px;
  font-size: 1.3rem;
  letter-spacing: 5px;
  color: hsl(210, 4%, 67%);
}

.testimonial-row {
  text-align: center;
}
/* EMILY */

.emily-image {
  border-radius: 100%;
  margin-bottom: 50px;
}

.emily-text {
   width: 65%;
   margin-left: 90px;
   font-family: 'Barlow', sans-serif;
   color:  hsl(212, 27%, 19%);
   font-weight: 500;
   line-height: 1.5;
}

.emily-name {
   font-family: 'Fraunces', serif;
   font-weight: bolder;
   margin-top: 45px;
}

.emily-position {
  color: hsl(213, 9%, 39%);
  font-family: 'Barlow', sans-serif;
  font-size: 0.8rem;
}

/* THOMAS */

.thomas-image {
  border-radius: 100%;
  margin-bottom: 50px;
}

.thomas-text {
  width: 65%;
  margin-left: 90px;
  font-family: 'Barlow', sans-serif;
  color:  hsl(212, 27%, 19%);
  font-weight: 500;
  line-height: 1.5;
}

.thomas-name {
  font-family: 'Fraunces', serif;
  font-weight: bolder;
  margin-top: 45px;
}

.thomas-position {
  color: hsl(213, 9%, 39%);
  font-family: 'Barlow', sans-serif;
  font-size: 0.8rem;
}

/* JENNIE */

.jennie-image {
  border-radius: 100%;
  margin-bottom: 50px;
}

.jennie-text {
  width: 65%;
  margin-left: 90px;
  font-family: 'Barlow', sans-serif;
  color:  hsl(212, 27%, 19%);
  font-weight: 500;
  line-height: 1.5;
}

.jennie-name {
  font-family: 'Fraunces', serif;
  font-weight: bolder;
  margin-top: 45px;
}

.jennie-position {
  color: hsl(213, 9%, 39%);
  font-family: 'Barlow', sans-serif;
  font-size: 0.8rem;
}

/* PROJECT SECTION */

.bottle-image {
  width: 100%;
}

.orange2-image {
  width: 100%;
}

.cone-image {
  width: 100%;
}

.sugar-image {
  width: 100%;
}

/* CONTACT SECTION */

#contact {
  padding: 9%;
  background-color:  hsl(168, 34%, 41%);
}

.bottom-brand-name {
  font-size: 1.5rem;
  color: hsl(167, 40%,24%);
  text-align: center;
  margin-top: -60px;
  padding-bottom: 20px;
  margin-left: 220px;
}

.links {
  margin-top: 20px;
  margin-left: 498px;
}

.bottom-link {
  text-decoration: none;
  color: hsl(167, 40%,24%);
  margin-left: 10px;
  padding-left: 15px;
}

.attribution {
  margin-bottom: 0px;
  margin-left: 350px;
  background-color: hsl(167, 40%,24%);
}

.icon-section {
  margin-left: 540px;
  margin-top: 50px;
  margin-bottom: -60px;
}

.icons {
  margin: 0 10px;
}



/* MEDIA QUERIES */

@media (min-width:1085px) and (max-width: 1940px) {
  /* h5 {
    margin-left: -100px
  }
} */
