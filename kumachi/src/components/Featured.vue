<template>
    <main>
        <section class="hero__container">
            <div class="hero__section__featured">
                <h1>Featured</h1>
                <p class="coffee__pastries">───── &nbsp;&nbsp; COFFEE PASTRIES &nbsp;&nbsp;─────</p>
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

        <section class="featured__container">
            <div class="featured__video__section">
                <div class="featured__content">
                    <h1>Kumachi</h1>
                    <p class="line__height">Experience the refined flavor of matcha in our beautifully crafted matcha
                        lattes. Below showcases this elegant green drink, offering a perfect balance of sweetness and
                        matcha's distinct earthiness. This cool beverage is ideal for both matcha enthusiasts and
                        newcomers alike.</p>
                </div>
                <div class="featured__video">
                    <video src="../assets/videos/Matcha.mp4" autoplay controls loop muted>
                        Your browser does not support the video tag.
                    </video>
                </div>
            </div>
            <div class="featured__images__section">
                <h3 class="text__center">Who we are</h3>
                <p class="text__center line__height">Kumachi is a local coffee shop that started as an online store on
                    Facebook and decided to establish their physical store, which has now been operating for more than a
                    month. Their objective and goals for the business is to let love delight in a person's heart through
                    innovative coffee experience.
                </p>
                <div class="featured__images__grid">
                    <div class="grid__short grid__short__index__column">
                        <img src="../assets/images/grid-image-1.webp" alt="Coffee">
                        <img src="../assets/images/grid-image-2.webp" alt="Matcha" class="span__two">
                        <img src="../assets/images/grid-image-3.webp" alt="Iced Coffee">
                    </div>
                    <div class="grid__long">
                        <div class="hidden"></div>
                        <img src="../assets/images/grid-image-4.webp" alt="Iced Coffee" class="span__three">
                        <img src="../assets/images/grid-image-5.webp" alt="Cake" class="span__three">
                        <div class="hidden"></div>
                    </div>
                    <div class="grid__short">
                        <img src="../assets/images/grid-image-6.webp" alt="Matcha Powder">
                        <img src="../assets/images/grid-image-7.webp" alt="Matcha Latte" class="span__two">
                        <img src="../assets/images/grid-image-8.webp" alt="Bread and Pastries">
                    </div>
                    <div class="grid__long">
                        <div class="hidden"></div>
                        <img src="../assets/images/grid-image-9.webp" alt="Iced Coffee" class="span__three">
                        <img src="../assets/images/grid-image-10.webp" alt="Kumachi Coffee" class="span__three">
                        <div class="hidden"></div>
                    </div>
                    <div class="grid__short grid__short__index__column">
                        <img src="../assets/images/grid-image-11.webp" alt="Egg Pie">
                        <img src="../assets/images/grid-image-12.webp" alt="Strawberry Coffee" class="span__two">
                        <img src="../assets/images/grid-image-13.webp" alt="Cake">
                    </div>
                </div>
            </div>
        </section>

        <section class="featured__facts__container">
            <div class="featured__facts__section">
                <div class="left__facts__section">
                    <h2>Did you know?</h2>
                    <p class="line__height">Kumachi’s mission and vision also came from the Bible verse 1 Corinthians
                        13:7, which describes ‘love as a safe place of shelter, for it never stops believing the best
                        for others.’ Moreover, their brand represents a bear that holds a cup of coffee, as 'love bears
                        all things'.</p>
                </div>
                <div class="right__facts__section">
                    <div class="fact__box">
                        <div class="fact__title">
                            <h4>The Origin of Coffee<br>─────</h4>
                            <i class="fa-solid fa-location-crosshairs"></i>
                        </div>
                        <p class="line__height">Legend has it that coffee was discovered by a goat herder in Ethiopia
                            who noticed his goats became unusually energetic after eating coffee berries. Since then,
                            coffee has become one of the most popular beverages worldwide, with over 2.25 billion cups
                            consumed daily!</p>
                    </div>
                    <div class="fact__box">
                        <div class="fact__title">
                            <h4>The Health Benefits of Coffee<br>─────</h4>
                            <i class="fa-solid fa-notes-medical"></i>
                        </div>
                        <p class="line__height">Not only does coffee give you that much-needed energy boost, but it also
                            comes with health benefits. Studies show that coffee is rich in antioxidants and can help
                            reduce the risk of certain diseases, including Type 2 diabetes, Alzheimer's, and
                            Parkinson’s.</p>
                    </div>
                    <div class="fact__box">
                        <div class="fact__title">
                            <h4>The Art of Brewing<br>─────</h4>
                            <i class="fa-solid fa-paint-roller"></i>
                        </div>
                        <p class="line__height">Did you know there are over 15 ways to brew coffee? From the classic
                            drip brew to the sophisticated pour-over or the robust French press, each method extracts
                            unique flavors, offering endless possibilities for your perfect cup.</p>
                    </div>
                    <div class="fact__box">
                        <div class="fact__title">
                            <h4>The Perfect Espresso Shot<br>─────</h4>
                            <i class="fa-solid fa-mug-saucer"></i>
                        </div>
                        <p class="line__height">Crafting the perfect espresso is an art in itself, requiring precise
                            pressure, water temperature, and grind size. A well-pulled espresso shot packs a powerful
                            punch of flavor and intensity in just 1 ounce, with a rich crema layer on top that signifies
                            a perfectly balanced brew.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="featured__products__container">
            <div class="featured__products__section">
                <div class="product__section__row">
                    <div class="featured__product__image">
                        <img src="../assets/images/featured-product-coffee.webp" alt="Kumachi Coffee">
                    </div>
                    <div class="featured__product__description">
                        <p class="featured__product__title">Cold and Hot Brew</p>
                        <p class="featured__sub__info">iced, classic, seasonal</p>
                        <p class="breaker__line">───</p>
                        <p class="featured__description">Our selection of cold and hot brews offers something for
                            everyone, whether you're craving a refreshing iced coffee to beat the heat or a comforting
                            hot cup to start your day. Enjoy a variety of seasonal flavors and classic favorites brewed
                            to perfection, always made with the finest Arabica beans for a smooth, rich taste in every
                            sip.</p>
                    </div>
                </div>
                <div class="product__section__row product__section__row__desktop">
                    <div class="featured__product__description">
                        <p class="featured__product__title">Cakes and Pastries</p>
                        <p class="featured__sub__info">cookies, bread, muffins</p>
                        <p class="breaker__line">───</p>
                        <p class="featured__description">Indulge in our freshly baked assortment of cakes and pastries,
                            perfect for pairing with your favorite coffee. From soft, chewy cookies to artisanal bread
                            and delicious muffins, each treat is crafted with care to bring you the best in flavor and
                            texture for a delightful snack any time of the day.</p>
                    </div>
                    <div class="featured__product__image">
                        <img src="../assets/images/featured-product-pastry.webp" alt="Kumachi Coffee">
                    </div>
                </div>

                <div class="product__section__row product__section__row__mobile">
                    <div class="featured__product__image">
                        <img src="../assets/images/featured-product-pastry.webp" alt="Kumachi Coffee">
                    </div>
                    <div class="featured__product__description">
                        <p class="featured__product__title">Cakes and Pastries</p>
                        <p class="featured__sub__info">cookies, bread, muffins</p>
                        <p class="breaker__line">───</p>
                        <p class="featured__description">Indulge in our freshly baked assortment of cakes and pastries,
                            perfect for pairing with your favorite coffee. From soft, chewy cookies to artisanal bread
                            and delicious muffins, each treat is crafted with care to bring you the best in flavor and
                            texture for a delightful snack any time of day.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="infographics__container">
            <h3 class="text__center infographics__title">Learn More About Coffee</h3>
            <p></p>
            <div class="infographics__section">
                <img src="../assets/images/infographics.webp" alt="Infographics" class="infographics">
            </div>
        </section>

        <section class="featured__container">
            <div class="featured__video__section">
                <div class="featured__content">
                    <h1>Matcha</h1>
                    <p class="line__height">Watch the artistry of creating matcha cookies come to life in this video.
                        From whisking the vibrant green matcha powder into the dough to baking them to perfection, this
                        step-by-step guide shows how these delightful cookies are made. Perfect for anyone looking to
                        learn the process or simply enjoy the satisfying visuals of matcha cookies being crafted.</p>

                </div>
                <div class="featured__video__2">
                    <video src="../assets/videos/Cookies.mp4" autoplay controls loop muted>
                        Your browser does not support the video tag.
                    </video>
                </div>
            </div>
        </section>

        <section class="difference__container">
            <div class="difference__section">
                <h3 class="text__center">What sets us different?</h3>
                <p class="text__center line__height">Crafting a unique coffee experience rooted in love, community, and
                    Japanese-inspired warmth, Kumachi blends quality and innovation to create an inviting space where
                    love truly bears all things.</p>
                <div class="difference__grid">
                    <div class="difference__grid__box">
                        <p class="difference__circle">1</p>
                        <p class="text__center">At our coffee shop, we bring the peaceful essence of Japanese culture
                            into every corner, creating a serene space where you can unwind with a perfect cup of
                            coffee.</p>
                    </div>
                    <div class="difference__grid__box">
                        <p class="difference__circle">2</p>
                        <p class="text__center">We ensure that each brew is made from the highest quality Arabica beans,
                            carefully sourced for a rich, smooth flavor in every sip.</p>
                    </div>
                    <div class="difference__grid__box">
                        <p class="difference__circle">3</p>
                        <p class="text__center">Open through the night, we're here to cater to your late-night cravings,
                            providing convenience whenever you need it.</p>
                    </div>
                    <div class="difference__grid__box">
                        <p class="difference__circle">4</p>
                        <p class="text__center">Despite our premium offerings, we keep our prices affordable, making
                            sure everyone can enjoy top-quality coffee without breaking the bank.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="cta__container">
            <div class="cta__section pad-top-5">
                <h3 class="text__center">Elevate Your Coffee Journey with the<span><br></span> Ultimate Experience
                    Today!</h3>
                <img src="../assets/images/Logo-Bear-Icon.webp" alt="Kumachi Logo" class="bear__icon">
                <p class="cta__p text__center">Immerse yourself in a warm and welcoming atmosphere where every
                    cup<span><br></span>is brewed to perfection using only the finest ingredients.</p>
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

<style src="../assets/css/featured.css" scoped>
</style>