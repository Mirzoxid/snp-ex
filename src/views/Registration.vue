<template>
  <div>
    <div id="root">
      <div class="outer-wrapper">
        <div class="wrapper wrapper_reg">
          <header class="page-header">
            <div class="container">
              <div class="page-headr__inner">
                <div class="page-header__logo">
                  <router-link to="dashboard" class="site-logo">
                    <img
                      src="@/assets/images/src/icons/site-logo.svg"
                      alt="Site-Logo"
                    />
                  </router-link>
                </div>
                <div class="page-header__sign">
                  <a href="#" class="page-header__btn btn">Log in</a>
                </div>
              </div>
            </div>
          </header>
          <section class="pg-section form-page">
            <div class="container">
              <div class="pg-section__inner">
                <div class="signup-page">
                  <div class="signup-page__head">
                    <h2 class="signup-page__title">Sign up now</h2>
                    <span class="signup-page__subtitle"
                      >and get access to:</span
                    >
                  </div>
                  <ul class="signup-page__list">
                    <li class="signup-page__item">
                      <div class="signup-page__icon">
                        <img src="@/assets/images/src/icons/iban.svg" alt="" />
                      </div>
                      <div class="signup-page__text">
                        Multi currency corporate IBAN accounts
                      </div>
                    </li>
                    <li class="signup-page__item">
                      <div class="signup-page__icon signup-page__icon_red">
                        <img src="@/assets/images/src/icons/fx.svg" alt="" />
                      </div>
                      <div class="signup-page__text">
                        Competitive FX rates for cross-border payments
                      </div>
                    </li>
                    <li class="signup-page__item">
                      <div class="signup-page__icon signup-page__icon_yellow">
                        <img src="@/assets/images/src/icons/card.svg" alt="" />
                      </div>
                      <div class="signup-page__text">
                        Merchant account for accepting card payments
                      </div>
                    </li>
                    <li class="signup-page__item">
                      <div class="signup-page__icon signup-page__icon_green">
                        <img src="@/assets/images/src/icons/chat.svg" alt="" />
                      </div>
                      <div class="signup-page__text">
                        Be part of an active payment community
                      </div>
                    </li>
                  </ul>
                  <div class="signup-page__footer">
                    <span class="signup-page__footer-text"
                      >We will ask you some information about your company, its
                      structure and transactions you are planning to make</span
                    >
                  </div>
                </div>
                <div class="form-page__wrapper">
                  <h2 class="form-page__title">Sign up</h2>
                  <form
                    action="#"
                    onsubmit="clickSignIn"
                    :class="{
                      'form-page__form': true,
                      'was-validated': checkValid,
                    }"
                    id="form"
                  >
                    <div class="form-page__wrp">
                      <label class="form-page__label"
                        >Your Name and Surname
                        <span class="form-page__required"
                          >(required)</span
                        ></label
                      >
                      <div class="form-page__pole">
                        <input
                          v-model="form['fullName']"
                          type="text"
                          class="form-page__input name-required"
                          id="form-page__input_required name"
                          value=""
                          required
                        />
                        <div class="icon-error">&#33;</div>
                        <div class="icon-done"></div>
                      </div>
                    </div>
                    <div class="form-page__wrp">
                      <label class="form-page__label"
                        >Your email address
                        <span class="form-page__required"
                          >(required)</span
                        ></label
                      >
                      <div class="form-page__pole">
                        <input
                          v-model="form['email']"
                          type="email"
                          class="form-page__input"
                          required
                          placeholder="ozodjon6@gmail.com"
                          id="email"
                        />
                        <div class="icon-error">&#33;</div>
                        <div class="icon-done">
                          <svg class="icon-done__check" width="10" height="8">
                            <use
                              xlink:href="assets/images/src/icons/sprite.svg#check"
                            ></use>
                          </svg>
                        </div>
                      </div>
                    </div>
                    <div class="form-page__wrp">
                      <label class="form-page__label"
                        >Pick a password
                        <span
                          class="form-page__required form-page__required_margin"
                          >(required)</span
                        ></label
                      >
                      <div class="form-page__question" id="question-btn">
                        <svg class="icon-question" width="6" height="8">
                          <use
                            xlink:href="assets/images/src/icons/sprite.svg#question"
                          ></use>
                        </svg>
                        <div class="form-page__answer">
                          Password is case sensitive and must contain: <br />
                          - at least 8 characters <br />
                          - at least one uppercase letter <br />
                          - at least one lowercase letter <br />
                          - at least one number <br />
                          - may NOT contain more than two identical characters
                          <br />
                          - may NOT be the same as last 3 passwords <br />
                        </div>
                      </div>
                      <div class="form-page__pole">
                        <input
                          v-model="form['password']"
                          type="password"
                          class="form-page__input form-page__input_valid"
                          id="password-field"
                          required
                        />
                        <div class="icon-error">&#33;</div>
                        <div class="icon-done"></div>
                        <ul class="checker-list">
                          <li class="checker-list__item checker-length">
                            <span class="checker-list__icon">
                              <svg class="icon-check" width="6" height="5">
                                <use
                                  xlink:href="assets/images/src/icons/sprite.svg#check"
                                ></use>
                              </svg>
                            </span>
                            8 or more characters
                          </li>
                          <li class="checker-list__item checker-number">
                            <span class="checker-list__icon">
                              <svg class="icon-check" width="6" height="5">
                                <use
                                  xlink:href="assets/images/src/icons/sprite.svg#check"
                                ></use>
                              </svg>
                            </span>
                            Numbers
                          </li>
                          <li class="checker-list__item checker-letters">
                            <span class="checker-list__icon">
                              <svg class="icon-check" width="6" height="5">
                                <use
                                  xlink:href="assets/images/src/icons/sprite.svg#check"
                                ></use>
                              </svg>
                            </span>
                            Letters
                          </li>
                          <li class="checker-list__item checker-special">
                            <span class="checker-list__icon">
                              <svg class="icon-check" width="6" height="5">
                                <use
                                  xlink:href="assets/images/src/icons/sprite.svg#check"
                                ></use>
                              </svg>
                            </span>
                            Special chacters
                          </li>
                        </ul>
                      </div>
                    </div>
                    <div class="form-page__wrp">
                      <label class="form-page__label"
                        >Confirm your password
                        <span class="form-page__required"
                          >(required)</span
                        ></label
                      >
                      <div class="form-page__pole">
                        <input
                          v-model="form['confirmPassword']"
                          type="password"
                          class="form-page__input form-page__input-confirm"
                          id="confirm-password"
                          required
                        />
                        <span id="message"></span>
                        <div class="icon-error">&#33;</div>
                        <div class="icon-done"></div>
                      </div>
                    </div>
                    <div class="form-page__wrp">
                      <div class="form-page__text">
                        By signing up, you're confirming you're OK with our
                        <a href="#" class="form-page__text_link"
                          >Privacy Policy</a
                        >
                      </div>
                    </div>
                    <div class="form-page__wrp">
                      <button
                        type="submit"
                        class="form-page__btn btn"
                        id="subBtn"
                        @click="clickSignIn"
                      >
                        Sign up
                      </button>
                    </div>
                    <div class="form-page__wrp">
                      <button
                        type="submit"
                        class="form-page__btn form-page__btn_disabled btn"
                        disabled
                      >
                        Sign up
                      </button>
                    </div>
                    <div class="form-page__wrp">
                      <div class="form-page__text form-page__text_login">
                        Already signed up?
                        <a
                          href="index-dashbord-menu.html"
                          class="form-page__text_link"
                          >Log in</a
                        >
                      </div>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </section>
        </div>
        <footer class="site-footer">
          <div class="container">
            <div class="site-footer__inner wow fadeInUp">
              <div class="site-footer__contact">
                <div class="site-footer__info">
                  <svg
                    class="site-footer__icon"
                    width="16"
                    height="10"
                    viewBox="0 0 16 10"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M0 1C0 0.447716 0.447715 0 1 0H15C15.5523 0 16 0.447715 16 1V9C16 9.55228 15.5523 10 15 10H1C0.447715 10 0 9.55229 0 9V1ZM3.89132 2L8 5.22825L12.1087 2H3.89132ZM14 3.05746L8 7.77175L2 3.05746V8H14V3.05746Z"
                      fill="#8C96A2"
                    />
                  </svg>
                  <a
                    href="email:support@safenetpay.com"
                    class="site-footer__email"
                    >support@safenetpay.com</a
                  >
                </div>
                <span class="site-footer__text">Online support</span>
              </div>
              <div class="site-footer__bottom">
                Safenetpay Services Company Ltd is incorporated in England
                (company number 10259575) with its registered office at 18 King
                William Street, Monument, London, EC4N 7BP, United Kingdom.
                Safenetpay Services Company Ltd is authorised by Financial
                Conduct Authority as Authorised Payment Institution with
                reference 795257 trading as Safenetpay. By virtue of this
                license Safenetpay is licensed to provide payment services.
                Safenetpay is registered trademark of Safenetpay Services
                Company Ltd. This website is owned and maintained by Safenetpay.
                By using this website, you agree to our Terms and Conditions. If
                you do not agree to these Terms and Conditions, please refrain
                from using this website.
              </div>
            </div>
          </div>
        </footer>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Registration extends Vue {
  @Prop() private msg!: string;

  private checkValid = false;

  private form = {
    fullName: "",
    email: "",
    password: "",
    confirmPassword: "",
  };

  private clickSignIn() {
    if (this.checkValid) {
      this.$router.push("dashboard");
    }

    this.checkValid = true;
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
