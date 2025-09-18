<template>
  <div
    class="cart-model__overlay"
    :class="{ open: isOpen }"
    @click.self="closeModal()"
  >
    <div class="cart-model">
      <div class="cart-model__header">
        <h2 class="cart-model__header--title">Корзина</h2>
        <span class="cart-model__header--close" @click="closeModal()">
          <img src="../assets/img/icons/close.svg" alt="close" />
        </span>
      </div>
      <div class="cart-model__body">
        <div class="cart-item">
          <p class="cart-item__title">Ролл угорь стандарт</p>
          <div class="cart-item__controls">
            <div class="cart-item__controls--price">250 ₽</div>
            <button class="btn btn-outline">-</button>
            <div class="cart-item__controls--count">1</div>
            <button class="btn btn-outline">+</button>
          </div>
        </div>
        <div class="cart-item">
          <p class="cart-item__title">Ролл угорь стандарт</p>
          <div class="cart-item__controls">
            <div class="cart-item__controls--price">250 ₽</div>
            <button class="btn btn-outline">-</button>
            <div class="cart-item__controls--count">1</div>
            <button class="btn btn-outline">+</button>
          </div>
        </div>
        <div class="cart-item">
          <p class="cart-item__title">Ролл угорь стандарт</p>
          <div class="cart-item__controls">
            <div class="cart-item__controls--price">250 ₽</div>
            <button class="btn btn-outline">-</button>
            <div class="cart-item__controls--count">1</div>
            <button class="btn btn-outline">+</button>
          </div>
        </div>
        <div class="cart-item">
          <p class="cart-item__title">Ролл угорь стандарт</p>
          <div class="cart-item__controls">
            <div class="cart-item__controls--price">250 ₽</div>
            <button class="btn btn-outline">-</button>
            <div class="cart-item__controls--count">1</div>
            <button class="btn btn-outline">+</button>
          </div>
        </div>
        <div class="cart-item">
          <p class="cart-item__title">Ролл угорь стандарт</p>
          <div class="cart-item__controls">
            <div class="cart-item__controls--price">250 ₽</div>
            <button class="btn btn-outline">-</button>
            <div class="cart-item__controls--count">1</div>
            <button class="btn btn-outline">+</button>
          </div>
        </div>
      </div>
      <div class="cart-model__footer">
        <div class="cart-model__foote--price">1250 ₽</div>
        <div class="cart-model__foote--controls">
          <button class="btn btn-primary">Оформить заказ</button>
          <button class="btn btn-outline">Отмена</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const { isOpen } = defineProps({ isOpen: Boolean });
const emit = defineEmits(["toggleModal"]);
const closeModal = () => emit("toggleModal");
</script>

<style scoped>
.cart-model__overlay {
  display: none;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: rgba(0, 0, 0, 0.4);
  align-items: center;
  justify-content: center;
}

.cart-model__overlay.open {
  display: flex;
}

.cart-model__header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 48px;
}

.cart-model__header--title {
  color: #000;
  font-size: 36px;
  font-weight: 700;
  margin: 0;
}

.cart-model__header--close {
  cursor: pointer;
}
.cart-model {
  width: 100%;
  max-width: 780px;
  padding: 40px 45px;
  border-radius: 5px;
  background: #fff;
}

.cart-model__footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 50px;
}

.cart-model__foote--price {
  border-radius: 5px;
  background: #262626;
  color: #fafafa;
  font-size: 20px;
  font-weight: 700;
  padding: 15px 20px;
}

.cart-model__foote--controls {
  display: flex;
  align-items: center;
  gap: 10px;
}

.cart-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 10px;
}

.cart-item:not(:last-child) {
  padding-bottom: 10px;
  margin-bottom: 10px;
  border-bottom: 1px solid #9d9d9d;
}

.cart-item__title {
  color: #000;
  font-size: 18px;
  font-weight: 400;
  line-height: 32px;
  margin: 0;
}

.cart-item__controls {
  display: flex;
  align-items: center;
}
.cart-item__controls--price {
  margin-right: 47px;
  color: #000;
  font-size: 20px;
  font-weight: 700;
  line-height: 32px;
}

.cart-item__controls button {
  border: 1px solid #40a9ff;
  color: #40a9ff;
}

.cart-item__controls--count {
  margin-left: 15px;
  margin-right: 15px;
}
</style>
