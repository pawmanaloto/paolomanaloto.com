<template>
  <div class="social-icons d-lg-block d-none">
    <ul class="social-icons__list">
      <li class="social-icons__item">
        <a
          href="https://github.com/pawmanaloto/"
          class="social-icons__link fa-lg text-white"
          target="_BLANK"
          rel="nofollow noopener noreferrer"
        >
          <fa-icon :icon="['fab', 'github']" />
        </a>
      </li>
      <li class="social-icons__item">
        <a
          href="https://ph.linkedin.com/in/paolo-ferdinand-manaloto"
          class="social-icons__link fa-lg text-white"
          target="_BLANK"
          rel="nofollow noopener noreferrer"
        >
          <fa-icon :icon="['fab', 'linkedin-in']" />
        </a>
      </li>
      <li class="social-icons__item">
        <a
          href="https://www.instagram.com/pawmanaloto/"
          class="social-icons__link fa-lg text-white"
          target="_BLANK"
          rel="nofollow noopener noreferrer"
        >
          <fa-icon :icon="['fab', 'instagram']" />
        </a>
      </li>
    </ul>
  </div>
</template>

<style lang="scss">
.social-icons {
  position: fixed;
  bottom: 1rem;
  left: 30px;

  &__list {
    list-style: none;
    padding: 0;
    margin-bottom: 0;

    &:after {
      content: "";
      display: block;
      width: 1px;
      height: 90px;
      margin: 0px auto;
      background-color: $color-light-white;
    }
  }

  &__link {
    display: block;
    position: relative;
    padding: 15px 10px;
    transition: all 0.3s ease;

    &:hover {
      color: $color-cyan !important;
      transform: translateY(-3px);
    }
  }
}
</style>
