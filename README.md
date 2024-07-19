It looks like the CSS for your ice cream shop landing page was cut off. I'll provide the missing portion and ensure that the transition effects, media queries, and other elements are included correctly.

Here's the continuation and completion of the CSS:

```css
/* Continuing CSS */

/* ------- HERO BUTTONS -------- */
.hero-btns-container {
  margin-top: 2rem;
  opacity: 0;
}
.in-btn-icon {
  margin-right: 0.5rem;
}

/* -------- SECTION TWO: Products -------- */
.section-two {
  margin-top: 5rem;
}
.s-two-upper-info {
  text-align: center;
}
.s-two-slogan {
  font-size: 2rem;
  color: var(--text-clr);
}
.s-two-definition {
  margin-top: 1rem;
}
.s-two-products {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  margin-top: 2rem;
}
.product {
  position: relative;
  background-color: var(--product-bg-clr);
  padding: 2rem;
  border-radius: 1rem;
  text-align: center;
  transition: transform 0.3s;
}
.product:hover {
  transform: translateY(-10px);
}
.product img {
  border-radius: 0.5rem;
}
.price, .buy-btn, .name {
  position: absolute;
  width: 100%;
  text-align: center;
  color: var(--text-clr);
  font-size: 1.2rem;
}
.price {
  top: 10px;
}
.buy-btn {
  bottom: 20px;
}
.name {
  bottom: 50px;
}

/* -------- SECTION THREE: Ad Section -------- */
.section-three {
  display: flex;
  justify-content: space-between;
  margin-top: 5rem;
}
.s-three-upper-img-container {
  flex-basis: 40%;
}
.s-three-lower-container {
  flex-basis: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.s-three-title {
  font-size: 2rem;
  color: var(--text-clr);
}
.s-three-desc {
  margin-top: 1rem;
}
.s-three-price {
  margin-top: 1.5rem;
  font-size: 2rem;
  color: var(--primary-clr);
}

/* -------- SECTION FOUR: About Section -------- */
.section-four {
  margin-top: 5rem;
  display: flex;
  justify-content: space-between;
}
.oath-container {
  flex-basis: 60%;
}
.s-four-title {
  font-size: 2rem;
  color: var(--text-clr);
}
.employer-info {
  display: flex;
  justify-content: space-between;
  margin-top: 2rem;
}
.employer {
  display: flex;
  flex-direction: column;
}
.name {
  font-size: 1.5rem;
}
.title {
  font-size: 1.2rem;
}
.rate img {
  width: 100px;
}
.waiter-img-container {
  flex-basis: 30%;
}

/* -------- SECTION FIVE: Promo Section -------- */
.section-five {
  margin-top: 5rem;
  text-align: center;
}
.promo-card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem;
  background-color: var(--primary-clr-alt);
  border-radius: 1rem;
}
.promo-info-container {
  flex-basis: 60%;
}
.promo-title {
  font-size: 2rem;
  color: var(--text-clr);
}
.promo-description {
  margin-top: 1rem;
}
.promo-btn {
  margin-top: 1.5rem;
}
.promo-card img {
  flex-basis: 35%;
  border-radius: 0.5rem;
}

/* -------- FOOTER -------- */
.footer {
  margin-top: 5rem;
  padding: 2rem 0;
  background-color: var(--bg-clr);
  color: var(--text-clr-bg);
}
.footer-title {
  text-align: center;
  font-size: 2rem;
}
.contact-form {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 2rem;
}
.form-control {
  margin-bottom: 1rem;
  width: 100%;
}
.form-label {
  font-size: 1rem;
  color: var(--text-clr);
}
.normal-input, .textarea-input {
  width: 100%;
  padding: 0.5rem;
  border: none;
  border-radius: 0.5rem;
  background-color: var(--form-bg-clr);
}
.normal-input:focus, .textarea-input:focus {
  background-color: var(--form-focus-bg-clr);
}
.textarea-input {
  height: 100px;
}
.send-msg-btn {
  margin-top: 1rem;
}
.other-footer-infos-container {
  margin-top: 2rem;
  display: flex;
  justify-content: space-around;
}
.footer-info {
  display: flex;
  align-items: center;
}
.footer-info i {
  margin-right: 0.5rem;
}
.footer-social-links ul {
  display: flex;
}
.footer-social-links ul li {
  margin-right: 1.5rem;
}
.lower-footer {
  margin-top: 2rem;
  display: flex;
  justify-content: space-between;
}
.lower-footer-elt {
  font-size: 1rem;
}
.lower-footer-elt a {
  color: var(--text-clr-bg);
  text-decoration: none;
}
.lower-footer-elt a:hover {
  text-decoration: underline;
}

/* -------- MEDIA QUERIES -------- */
@media screen and (max-width: 768px) {
  .section-two .s-two-products {
    flex-direction: column;
    align-items: center;
  }
  .section-three, .section-four {
    flex-direction: column;
    align-items: center;
  }
  .promo-card {
    flex-direction: column;
    align-items: center;
  }
}
```

This should complete the CSS and HTML for your ice cream shop landing page. Feel free to modify the styles and content as needed. If you have any specific requirements or further questions, let me know!
