<template>
  <section class="product">
    <div class="container">
      <div class="products-wrapper" id="goods-container">
        <div class="products-card">
          <div class="products-card__image">
            <img src="../assets/img/goods/goods-1.jpg" alt="goods-1" />
          </div>
          <div class="products-card__description">
            <div class="products-card__description-row">
              <h5 class="products-card__description--name">
                Ролл угорь стандарт
              </h5>
            </div>
            <div class="products-card__description-row">
              <p class="products-card__description--text">
                Рис, угорь, соус унаги, кунжут, водоросли нори.
              </p>
            </div>
            <div class="products-card__description-row">
              <div class="products-card__description-controls">
                <button class="btn btn-primary">
                  В корзину
                  <img
                    src="../assets/img/icons/shopping-cart-white.svg"
                    alt="shopping-cart"
                  />
                </button>
                <span class="products-card__description-controls--price">
                  250 ₽
                </span>
              </div>
            </div>
          </div>
        </div>
        <div class="products-card">
          <div class="products-card__image">
            <img src="../assets/img/goods/goods-2.jpg" alt="goods-2" />
          </div>
          <div class="products-card__description">
            <div class="products-card__description-row">
              <h5 class="products-card__description--name">
                Калифорния лосось стандарт
              </h5>
            </div>
            <div class="products-card__description-row">
              <p class="products-card__description--text">
                Рис, лосось, авокадо, огурец, майонез, икра масаго, водоросли
                нори.
              </p>
            </div>
            <div class="products-card__description-row">
              <div class="products-card__description-controls">
                <button class="btn btn-primary">
                  В корзину
                  <img
                    src="../assets/img/icons/shopping-cart-white.svg"
                    alt="shopping-cart"
                  />
                </button>
                <span class="products-card__description-controls--price">
                  395 ₽
                </span>
              </div>
            </div>
          </div>
        </div>
        <div class="products-card">
          <div class="products-card__image">
            <img src="../assets/img/goods/goods-3.jpg" alt="goods-3" />
          </div>
          <div class="products-card__description">
            <div class="products-card__description-row">
              <h5 class="products-card__description--name">Окинава стандарт</h5>
            </div>
            <div class="products-card__description-row">
              <p class="products-card__description--text">
                Рис, креветка отварная, сыр сливочный, лосось, огурец свежий...
              </p>
            </div>
            <div class="products-card__description-row">
              <div class="products-card__description-controls">
                <button class="btn btn-primary">
                  В корзину
                  <img
                    src="../assets/img/icons/shopping-cart-white.svg"
                    alt="shopping-cart"
                  />
                </button>
                <span class="products-card__description-controls--price">
                  250 ₽
                </span>
              </div>
            </div>
          </div>
        </div>
        <div class="products-card">
          <div class="products-card__image">
            <img src="../assets/img/goods/goods-4.jpg" alt="goods-4" />
          </div>
          <div class="products-card__description">
            <div class="products-card__description-row">
              <h5 class="products-card__description--name">Цезарь маки хl</h5>
            </div>
            <div class="products-card__description-row">
              <p class="products-card__description--text">
                Рис, куриная грудка копченая, икра масаго, томат, айсберг, соус
                цезарь...
              </p>
            </div>
            <div class="products-card__description-row">
              <div class="products-card__description-controls">
                <button class="btn btn-primary">
                  В корзину
                  <img
                    src="../assets/img/icons/shopping-cart-white.svg"
                    alt="shopping-cart"
                  />
                </button>
                <span class="products-card__description-controls--price">
                  250 ₽
                </span>
              </div>
            </div>
          </div>
        </div>
        <div class="products-card">
          <div class="products-card__image">
            <img src="../assets/img/goods/goods-5.jpg" alt="goods-5" />
          </div>
          <div class="products-card__description">
            <div class="products-card__description-row">
              <h5 class="products-card__description--name">
                Ясай маки стандарт 185 г
              </h5>
            </div>
            <div class="products-card__description-row">
              <p class="products-card__description--text">
                Рис, помидор свежий, перец болгарский, авокадо, огурец, айсберг
              </p>
            </div>
            <div class="products-card__description-row">
              <div class="products-card__description-controls">
                <button class="btn btn-primary">
                  В корзину
                  <img
                    src="../assets/img/icons/shopping-cart-white.svg"
                    alt="shopping-cart"
                  />
                </button>
                <span class="products-card__description-controls--price">
                  250 ₽
                </span>
              </div>
            </div>
          </div>
        </div>
        <div class="products-card">
          <div class="products-card__image">
            <img src="../assets/img/goods/goods-6.jpg" alt="goods-6" />
          </div>
          <div class="products-card__description">
            <div class="products-card__description-row">
              <h5 class="products-card__description--name">
                Ролл с креветкой стандарт
              </h5>
            </div>
            <div class="products-card__description-row">
              <p class="products-card__description--text">
                Рис, водоросли нори, креветки отварные, сыр сливочный, огурцы
              </p>
            </div>
            <div class="products-card__description-row">
              <div class="products-card__description-controls">
                <button class="btn btn-primary">
                  В корзину
                  <img
                    src="../assets/img/icons/shopping-cart-white.svg"
                    alt="shopping-cart"
                  />
                </button>
                <span class="products-card__description-controls--price">
                  250 ₽
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const restArray = [
  {
    id: 0,
    title: "Пицца плюс",
    time: 50,
    rating: 4.5,
    price: 900,
    type: "Питтца",
    image: "rest-1.jpg",
  },
  {
    id: 1,
    title: "Тануки",
    time: 50,
    rating: 4.5,
    price: 900,
    type: "Питтца",
    image: "rest-2.jpg",
  },
  {
    id: 2,
    title: "FoodBand",
    time: 50,
    rating: 4.5,
    price: 900,
    type: "Питтца",
    image: "rest-3.jpg",
  },
  {
    id: 3,
    title: "Жадины-пицца",
    time: 50,
    rating: 4.5,
    price: 900,
    type: "Питтца",
    image: "rest-4.jpg",
  },
  {
    id: 4,
    title: "Точка еды",
    time: 50,
    rating: 4.5,
    price: 900,
    type: "Питтца",
    image: "rest-5.jpg",
  },
  {
    id: 5,
    title: "PizzaBurger",
    time: 50,
    rating: 4.5,
    price: 900,
    type: "Питтца",
    image: "rest-6.jpg",
  },
];
</script>
