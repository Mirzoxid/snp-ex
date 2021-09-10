<template>
  <div class="main-bg">
    <div id="root">
      <div class="outer-wrapper">
        <div class="wrapper">
          <!-- <div class="blank-block"></div> -->
          <aside class="sidebar-menu">
            <div class="sidebar-menu__head">
              <div class="sidebar-menu-logo">
                <a href="#" class="site-logo">
                  <img src="@/assets/images/src/icons/site-logo.svg" alt="">
                </a>
                <a href="#" class="snp-logo snp-logo__sidebar">
                  <img src="@/assets/images/src/icons/snp-logo.svg" alt="">
                </a>
              </div>
              <div class="account-user account-user__sidebar d-flex a-center">
                <div class="account-user__logo">
                  <img src="@/assets/images/src/img/user-jpeg.jpg" alt="">
                </div>
                <span class="account-user__name">Welcome, User</span>
                <div class="account-user__sidebar-close" id="close-sidebar">
                  <svg class=" icon-svg" width="12" height="12">
                    <use xlink:href="@/assets/images/src/icons/sprite-all.svg#close"></use>
                  </svg>
                </div>
              </div>
            </div>
            <div class="sidebar-menu__body">
              <div class="company-info">
                <div class="company-info__list">
                  <div class="company-info__item">
                    <div class="company-info__inner">
                      <a href="#" class="company-info__link">1. Company information</a>
                      <svg class="company-info__icon icon-svg" width="10" height="7.5">
                        <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check-green"></use>
                      </svg>
                      <i class="company-info__warning">
                        <svg class="icon-warning icon-svg" width="2" height="8">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                        </svg>
                      </i>
                    </div>
                  </div>
                  <div class="company-info__item">
                    <div class="company-info__inner">
                      <a href="#" class="company-info__link">2. Transaction information</a>
                      <svg class="company-info__icon icon-svg" width="10" height="7.5">
                        <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check-green"></use>
                      </svg>
                      <i class="company-info__warning">
                        <svg class="icon-warning icon-svg" width="2" height="8">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                        </svg>
                      </i>
                    </div>
                  </div>
                  <div class="company-info__item ">
                    <div class="company-info__inner">
                      <a href="#" class="company-info__link">3. Company structure</a>
                      <svg class="company-info__icon icon-svg" width="10" height="7.5">
                        <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check-green"></use>
                      </svg>
                      <i class="company-info__warning">
                        <svg class="icon-warning icon-svg" width="2" height="8">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                        </svg>
                      </i>
                    </div>
                  </div>
                  <div class="company-info__item">
                    <div class="company-info__inner">
                      <a href="#" class="company-info__link">4. Upload documents</a>
                      <svg class="company-info__icon icon-svg" width="10" height="7.5">
                        <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check-green"></use>
                      </svg>
                      <i class="company-info__warning">
                        <svg class="icon-warning icon-svg" width="2" height="8">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                        </svg>
                      </i>
                    </div>
                  </div>
                  <div class="company-info__item">
                    <div class="company-info__inner">
                      <a href="#" class="company-info__link">5. Review and submit</a>
                      <svg class="company-info__icon icon-svg" width="10" height="7.5">
                        <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check-green"></use>
                      </svg>
                      <i class="company-info__warning">
                        <svg class="icon-warning icon-svg" width="2" height="8">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                        </svg>
                      </i>
                    </div>
                  </div>
                </div>
                <div class="company-info__content">
                  <a href="#" class="company-info__save btn">Save your progress</a>
                  <button class="company-info__restart btn">Restart your application</button>
                  <div class="company-info__percent">0%</div>
                </div>

              </div>
              <div class="dashboard-menu">
                <ul class="dashboard-menu__list">
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#dashboard"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Dashboard</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Transfer money</a>
                              </li>
                              <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Active page item</a>
                              </li>
                              <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Reports</a>
                              </li>
                              <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Hover item</a>
                              </li>
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#icon-home"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Accounts</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li>
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#arrow-right"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Send money</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#person"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Beneficiaries</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#crypto"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Crypto</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#exchange"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Exchange</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#merchant-account"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Merchant account</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#reports"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Reports</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#message"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Messages</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#community"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Community</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#faq"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">FAQ</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mobile-phone"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Mobile application</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#settings"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Settings</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item">
                    <ul class="dashboard-menu__inner">
                      <li class="dashboard-menu__type">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#log-out"></use>
                          </svg>
                        </a>
                      </li>
                      <li class="dashboard-menu__content">
                        <div class="dashboard-menu__content-wrap">
                          <div class="dashboard-menu__title">
                            <div class="dashboard-menu__title-text">Log out</div>
                          </div>
                          <div class="dashboard-menu__wrapper">
                            <ul class="dropdown-list">
                              <!-- <li class="dropdown-list__item">
                                <a href="#" class="dropdown-list__link">Item-1</a>
                              </li> -->
                            </ul>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </li>
                  <li class="dashboard-menu__item dashboard-menu__item_next" id="sidebar-js">
                    <ul class="dashboard-menu__inner dashboard-menu__inner_next">
                      <li class="dashboard-menu__type dashboard-menu__type_next">
                        <a href="#" class="dashboard-menu__icon">
                          <svg class="sidebar-icon sidebar-icon_open" width="16" height="16">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#arrow-right"></use>
                          </svg>
                        </a>
                      </li>
                    </ul>
                  </li>
                </ul>
              </div>
            </div>
            <div class="sidebar-menu__footer"></div>
          </aside>
          <main class="main-page" id="main">
            <header class="page-header header-1">
              <div class="container custom-container">
                <div class="page-headr__inner page-header__dashboard">
                  <div class="page-header__tab-logo">
                    <a href="#" class="site-logo site-logo__tab">
                      <img src="@/assets/images/src/icons/site-logo.svg" alt="">
                    </a>
                  </div>
                  <div class="page-heaedr__left d-flex a-center">
                    <div class="account-view d-flex a-center">
                      <div class="account-view__title">GBP account:</div>
                      <div class="account-view__count">
                        £ <strong class="count-strong">28,900.10</strong>
                        <svg class="account-view__count-icon icon-up" width="7" height="3.5">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#up-down"></use>
                        </svg>
                        <div class="account-view__currency">
                          <div class="currency-country">
                            £ <strong class="count-strong">28,900.10</strong>
                            <img src="@/assets/images/src/icons/flag-uk.svg" alt="">
                          </div>
                          <div class="currency-country">
                            € <strong class="count-strong">00.00</strong>
                            <img src="@/assets/images/src/icons/flag-eu.svg" alt="">
                          </div>
                          <a href="#" class="account-view__btn btn">Open acconts</a>
                        </div>
                      </div>
                      <svg class="account-view__icon icon-svg icon-easy">
                        <use xlink:href="@/assets/images/src/icons/sprite-all.svg#icon-easy"></use>
                      </svg>
                    </div>
                    <div class="page-header__application">
                      <div class="app-status d-flex a-center">
                        <div class="app-status__name">Application status:</div>
                        <div class="app-status__box is-active">
                          <svg class="app-status__icon status-icon">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#under-review"></use>
                          </svg>
                          <div class="app-status__text">Under review</div>
                        </div>
                        <div class="app-status__box app-status__box_orange">
                          <svg class="app-status__icon">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#warrning-yellow"></use>
                          </svg>
                          <div class="app-status__text">Update required</div>
                        </div>
                        <div class="app-status__box app-status__box_red">
                          <svg class="app-status__icon status-icon">
                            <use xlink:href="@/assets/images/src/icons/sprite-all.svg#error-x"></use>
                          </svg>
                          <div class="app-status__text">Declined</div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="page-header__right">
                    <div class="account-user d-flex a-center">
                      <a href="#" class="account-user__activate btn">Activate business account</a>
                      <div class="account-user__wrp">
                        <div class="account-user__logo">
                          <img src="@/assets/images/src/img/user-jpeg.jpg" alt="">
                        </div>
                        <span class="account-user__name">Welcome, User</span>
                      </div>
                      <div class="account-user__message">
                        <svg class="account-user__icon icon-svg icon-message">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#message"></use>
                        </svg>
                        <div class="message-inbox">
                          <div class="mesasge-inbox__title title">Inbox</div>
                          <div class="message-inbox__subtitle">You have 1 new message</div>
                          <a href="#" class="message-inbox__btn btn">Open message center</a>
                        </div>
                      </div>
                      <div class="account-user__moon">
                        <svg class="account-user__icon icon-svg icon-moon">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#moon"></use>
                        </svg>
                      </div>
                      <div class="account-user__humburger" id="sidebar-js">
                        <svg class="account-user__icon icon-svg icon-moon">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#humburger"></use>
                        </svg>
                      </div>
                      <span class="account-user__logout">Log out</span>
                    </div>
                  </div>
                </div>
                <div class="page-header__mobile"></div>
              </div>
            </header>
            <section class="pg-section welcome-page">
              <div class="container">
                <div class="welcome-page__inner">
                  <div class="welcome-page__logo">
                    <a href="#" class="snp-logo">
                      <img src="@/assets/images/src/icons/snp-logo.svg" alt="">
                    </a>
                  </div>
                  <h2 class="welcome-page__title title">Hey Farkhod, welcome to Safenetpay</h2>
                  <div class="welcome-page__descr descr">Your account is almost ready to go. We need some more information to activate it.</div>
                </div>
              </div>
            </section>
            <section class="pg-section activate-page">
              <div class="container perfect-container">
                <div class="activate-page__inner">
                  <div class="activate-page__header">
                    <h2 class="activate-page__title title">Activate your account</h2>
                    <div class="activate-page__descr descr">Complete in any order you like</div>
                  </div>
                  <div class="activate-page__body">
                    <div class="active-account">
                      <div class="active-account__list">
                        <div class="active-account__item br-top br-bottom" aria-disabled="">
                          <div class="clcik-page d-flex a-center">
                            <div class="click-page__numbers is-success">
                              <span class="click-page__number">1</span>
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success active">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                            </div>
                            <div class="click-page__name active">
                              <h3 class="click-page__title title">Company information</h3>
                              <!-- <span class="click-page__descr descr"></span> -->
                            </div>
                            <div class="click-page__icons is-success">
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success active">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                              <i class="click-page__right">
                                <svg class="icon-right icon-svg" width="9" height="16">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#back-icon"></use>
                                </svg>
                              </i>
                            </div>
                          </div>
                          <a href="#" class="active-account__click-to"></a>
                        </div>
                        <div class="active-account__item br-bottom">
                          <div class="clcik-page d-flex a-center">
                            <div class="click-page__numbers is-active">
                              <span class="click-page__number active">2</span>
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                            </div>
                            <div class="click-page__name">
                              <h3 class="click-page__title title">Transaction information</h3>
                              <span class="click-page__descr descr">Tell us how you'll use your account</span>
                            </div>
                            <div class="click-page__icons is-right">
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                              <i class="click-page__right active">
                                <svg class="icon-right icon-svg" width="9" height="16">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#back-icon"></use>
                                </svg>
                              </i>
                            </div>
                          </div>
                          <a href="index-dashboard-3.html" class="active-account__click-to"></a>
                        </div>
                        <div class="active-account__item br-bottom">
                          <div class="clcik-page d-flex a-center">
                            <div class="click-page__numbers is-active">
                              <span class="click-page__number active">3</span>
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                            </div>
                            <div class="click-page__name">
                              <h3 class="click-page__title title">Company structure</h3>
                              <span class="click-page__descr descr">Tell us about your directors and shareholders</span>
                            </div>
                            <div class="click-page__icons is-right">
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                              <i class="click-page__right active">
                                <svg class="icon-right icon-svg" width="9" height="16">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#back-icon"></use>
                                </svg>
                              </i>
                            </div>
                          </div>
                          <a href="index-dashboard-4.html" class="active-account__click-to"></a>
                        </div>
                        <div class="active-account__item br-bottom">
                          <div class="clcik-page d-flex a-center">
                            <div class="click-page__numbers is-active">
                              <span class="click-page__number active">4</span>
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                            </div>
                            <div class="click-page__name">
                              <h3 class="click-page__title title">Upload documents</h3>
                              <span class="click-page__descr descr">Upload supporting documents</span>
                            </div>
                            <div class="click-page__icons is-right">
                              <i class="click-page__warning">
                                <svg class="icon-warning icon-svg" width="4" height="10">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#mark-icon"></use>
                                </svg>
                              </i>
                              <i class="click-page__success">
                                <svg class="icon-success icon-svg" width="10" height="8">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#check"></use>
                                </svg>
                              </i>
                              <i class="click-page__right active">
                                <svg class="icon-right icon-svg" width="9" height="16">
                                  <use xlink:href="@/assets/images/src/icons/sprite-all.svg#back-icon"></use>
                                </svg>
                              </i>
                            </div>
                          </div>
                          <a href="index-dashboard-10.html" class="active-account__click-to"></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
          </main>
        </div>
        <aside class="site-footer__dashboard">
          <div class="container">
            <div class="dashboard-menu dashboard-menu__tab">
              <ul class="dashboard-menu__list dashboard-menu__list_tab">
                <li class="dashboard-menu__item dashboard-menu__item_tab">
                  <ul class="dashboard-menu__inner dashboard-menu__inner_tab">
                    <li class="dashboard-menu__type">
                      <a href="#" class="dashboard-menu__icon dashboard-menu__link_tab">
                        <svg class="sidebar-icon dashboard-menu__icon_tab" width="24" height="24">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#dashboard"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="dashboard-menu__content dashboard-menu__content_tab">
                      <div class="dashboard-menu__content-wrap dashboard-menu__content-wrap_tab">
                        <div class="dashboard-menu__title dashboard-menu__title_tab">Dashboard</div>
                        <div class="dashboard-menu__wrapper"> dashboard-menu__title_tab
                          <ul class="dropdown-list">
                            <!-- <li class="dropdown-list__item">
                              <a href="#" class="dropdown-list__link">Item-1</a>
                            </li> -->
                          </ul>
                        </div>
                      </div>
                    </li>
                  </ul>
                </li>
                <li class="dashboard-menu__item dashboard-menu__item_tab">
                  <ul class="dashboard-menu__inner dashboard-menu__inner_tab">
                    <li class="dashboard-menu__type">
                      <a href="#" class="dashboard-menu__icon dashboard-menu__link_tab">
                        <svg class="sidebar-icon dashboard-menu__icon_tab" width="22" height="24">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#icon-home"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="dashboard-menu__content dashboard-menu__content_tab">
                      <div class="dashboard-menu__content-wrap dashboard-menu__content-wrap_tab">
                        <div class="dashboard-menu__title dashboard-menu__title_tab">Accounts</div>
                        <div class="dashboard-menu__wrapper">
                          <ul class="dropdown-list">
                            <!-- <li class="dropdown-list__item">
                              <a href="#" class="dropdown-list__link">Item-1</a>
                            </li> -->
                          </ul>
                        </div>
                      </div>
                    </li>
                  </ul>
                </li>
                <li class="dashboard-menu__item dashboard-menu__item_tab">
                  <ul class="dashboard-menu__inner dashboard-menu__inner_tab">
                    <li class="dashboard-menu__type">
                      <a href="#" class="dashboard-menu__icon dashboard-menu__link_tab">
                        <svg class="sidebar-icon dashboard-menu__icon_tab" width="18" height="23">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#person"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="dashboard-menu__content dashboard-menu__content_tab">
                      <div class="dashboard-menu__content-wrap dashboard-menu__content-wrap_tab">
                        <div class="dashboard-menu__title dashboard-menu__title_tab">Beneficiaries</div>
                        <div class="dashboard-menu__wrapper">
                          <ul class="dropdown-list">
                            <!-- <li class="dropdown-list__item">
                              <a href="#" class="dropdown-list__link">Item-1</a>
                            </li> -->
                          </ul>
                        </div>
                      </div>
                    </li>
                  </ul>
                </li>
                <li class="dashboard-menu__item dashboard-menu__item_tab dashboard-menu__item_mobile">
                  <ul class="dashboard-menu__inner dashboard-menu__inner_tab">
                    <li class="dashboard-menu__type">
                      <a href="#" class="dashboard-menu__icon dashboard-menu__link_tab">
                        <svg class="sidebar-icon dashboard-menu__icon_tab" width="16" height="24">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#crypto"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="dashboard-menu__content dashboard-menu__content_tab">
                      <div class="dashboard-menu__content-wrap dashboard-menu__content-wrap_tab">
                        <div class="dashboard-menu__title dashboard-menu__title_tab">Crypto</div>
                        <div class="dashboard-menu__wrapper">
                          <ul class="dropdown-list">
                            <!-- <li class="dropdown-list__item">
                              <a href="#" class="dropdown-list__link">Item-1</a>
                            </li> -->
                          </ul>
                        </div>
                      </div>
                    </li>
                  </ul>
                </li>
                <li class="dashboard-menu__item dashboard-menu__item_tab dashboard-menu__item_mobile">
                  <ul class="dashboard-menu__inner dashboard-menu__inner_tab">
                    <li class="dashboard-menu__type">
                      <a href="#" class="dashboard-menu__icon dashboard-menu__link_tab">
                        <svg class="sidebar-icon dashboard-menu__icon_tab" width="24" height="21">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#exchange"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="dashboard-menu__content dashboard-menu__content_tab">
                      <div class="dashboard-menu__content-wrap dashboard-menu__content-wrap_tab">
                        <div class="dashboard-menu__title dashboard-menu__title_tab">Exchange</div>
                        <div class="dashboard-menu__wrapper">
                          <ul class="dropdown-list">
                            <!-- <li class="dropdown-list__item">
                              <a href="#" class="dropdown-list__link">Item-1</a>
                            </li> -->
                          </ul>
                        </div>
                      </div>
                    </li>
                  </ul>
                </li>
                <li class="dashboard-menu__item dashboard-menu__item_tab" id="sidebar-js">
                  <ul class="dashboard-menu__inner dashboard-menu__inner_tab">
                    <li class="dashboard-menu__type">
                      <a href="#" class="dashboard-menu__icon dashboard-menu__link_tab">
                        <svg class="sidebar-icon dashboard-menu__icon_tab" width="24" height="24">
                          <use xlink:href="@/assets/images/src/icons/sprite-all.svg#humburger"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="dashboard-menu__content dashboard-menu__content_tab">
                      <div class="dashboard-menu__content-wrap dashboard-menu__content-wrap_tab">
                        <div class="dashboard-menu__title dashboard-menu__title_tab">More</div>
                        <div class="dashboard-menu__wrapper">
                          <ul class="dropdown-list">
                            <!-- <li class="dropdown-list__item">
                              <a href="#" class="dropdown-list__link">Item-1</a>
                            </li> -->
                          </ul>
                        </div>
                      </div>
                    </li>
                  </ul>
                </li>
              </ul>
            </div>
          </div>
        </aside>
        <!-- <footer class="site-footer site-footer__dashboard">
          <div class="container">

          </div>
        </footer> -->
      </div>
    </div>
    <div class="overlay"></div>
    <div class="quiz-popup">
      <div class="quiz-popup__inner">
        <div class="quiz-popup__question">Are you sure to delete?</div>
        <div class="quiz-popup__user-name">FLASH DIAMOND BUSINESS</div>
        <div class="quiz-popup__btns d-flex a-center">
          <button class="quiz-popup__btn btn btn-left">Yes</button>
          <button class="quiz-popup__btn btn btn-right" id="close-btn">Cancel</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Dashboard extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
