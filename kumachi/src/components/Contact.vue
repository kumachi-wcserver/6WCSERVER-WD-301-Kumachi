<template>
    <main>
        <section class="hero__container">
            <div class="hero__section__contact">      
                <h1>Contact</h1>
                <!-- <p class="coffee__pastries">─────  &nbsp;&nbsp; COFFEE PASTRIES &nbsp;&nbsp;─────</p> -->
            </div>
        </section>

        <section id="cart-sidebar" class="cart">
            <h3>Your Cart</h3>
            <button class="cart-close">✕</button>
            <div id="cart-items"></div>
            <div id="cart-total"></div>
            <button class="clear-cart">Clear Cart</button> 
            <button class="checkout">Checkout</button>
        </section>

        <section class="contact__container">
            <div class="contact__intro">
                <h3 class="text__center">Get in touch</h3>
                <p class="text__center line__height medium-size">Connect with us for any questions, feedback, or just to share your coffee experience. You can visit our store, reach us via phone, Facebook, or Instagram, or use the message form below. Our team is here to ensure every interaction is as delightful as our coffee. We value your input and look forward to making your experience with us even better. Let's keep the conversation brewing. 
                </p>
            </div>
            <div class="contact__section">
                <div class="contact__left">
                    <div class="contact__left__content">
                        <h4 class="contact__heading">Visit Us</h4>
                        <p class="medium-size">B21 L10 NHA Pandacaqui, Mexico, San Fernando, Pampanga, Philippines</p>                        
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d742.3167524887035!2d120.64948429315483!3d15.176855047007724!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3396ef002db90f01%3A0xb8f33fa33297bf1a!2sKumachi!5e0!3m2!1sen!2sph!4v1726578945100!5m2!1sen!2sph" style="border:0; width: 100%; height: 15rem;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </div>
                    <div class="contact__left__content">
                        <h4 class="contact__heading">Reach Us</h4>
                        <p class="medium-size">Contact us through mobile and our social media accounts. Get engaged with our coffee community.</p>
                        <div class="contact__detail">
                            <router-link to="tel:09971467790" target="_blank"><img src="../assets/images/icons/phone.webp" alt="Phone Icon" class=""></router-link>
                            <router-link to="tel:09971467790" target="_blank" class="contact__link medium-size">0997 146 7790</router-link>
                        </div>
                        <div class="contact__detail">
                            <router-link to="https://www.facebook.com/profile.php?id=61560583146776" target="_blank"><img src="../assets/images/icons/facebook.webp" alt="Facebook Logo" class=""></router-link>
                            <router-link to="https://www.facebook.com/profile.php?id=61560583146776" target="_blank" class="contact__link medium-size">Kumachi くまち</router-link>
                        </div>
                        <div class="contact__detail">
                            <router-link to="https://www.instagram.com/kumachi_coffee.ph/" target="_blank"><img src="../assets/images/icons/instagram.webp" alt="Instagram Logo" class=""></router-link>
                            <router-link to="https://www.instagram.com/kumachi_coffee.ph/" target="_blank" class="contact__link medium-size">kumachi_coffee.ph</router-link>
                        </div>
                    </div>
                </div>
                <div class="contact__right">
                    <div class="contact__right__content medium-size">
                        <h4 class="contact__right__heading">Send a Message</h4>
                        <p>Have questions or feedback? We're here to help you enjoy every moment with us.</p>
                        <form class="medium-size">
                            <label for="name" class="contact__input__label line__height">Name:</label><input type="text" name="name" id="name" class="contact__input">

                            <label for="email" class="contact__input__label line__height">Email Address:</label><input type="email" name="email" id="email" class="contact__input">

                            <label for="num" class="contact__input__label line__height">Mobile Number:</label><input type="number" name="num" id="num" class="contact__input">

                            <label for="subject" class="contact__input__label line__height">Subject:</label><input type="text" name="subject" id="subject" class="contact__input">

                            <label for="message" class="contact__input__label line__height">Message:</label><textarea name="message" id="message" class="contact__input"></textarea>
                            <div class="contact__buttons">
                                <button class="contact__button button__outline__light" type="reset">Reset</button>
                                <button class="contact__button button__light" type="submit">Submit</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <section class="cta__container">
            <div class="cta__section pad-top-5">
                <h3 class="text__center">Elevate Your Coffee Journey with the<span><br></span> Ultimate Experience Today!</h3>
                <img src="../assets/images/Logo-Bear-Icon.webp" alt="Kumachi Logo" class="bear__icon">
                <p class="cta__p text__center">Immerse yourself in a warm and welcoming atmosphere where every cup<span><br></span>is brewed to perfection using only the finest ingredients.</p>
                <router-link to="/products#products__section"><button class="button__colored">Grab a Coffee</button></router-link>
            </div>
        </section>
    </main>
</template>

<script>
export default {
  beforeRouteEnter(to, from, next) {
    next(vm => {
      const alreadyReloaded = localStorage.getItem('pageReloaded');
      
      if (!alreadyReloaded) {
        localStorage.setItem('pageReloaded', 'true');
        location.reload();
      } else {
        localStorage.removeItem('pageReloaded');
      }
    });
  }
};
</script>

<style src="../assets/css/contact.css" scoped>
</style>