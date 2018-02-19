<template>
  <div class="header">
    <div class="header-container">
      <a class="logo" href="//www.youzan.com"></a>
      <ul class="nav">
        <li>
          <a href="#">首页</a>
        </li>
        <li class="dropdown">
          <a href="javascript:;">产品和解决方案</a>
          <div class="arrow">
            <svg class="icon" aria-hidden="true">
              <use xlink:href="#icon-arrowdown"></use>
            </svg>
          </div>
          <div class="dropdown-menu">
            <div class="dropdown-menu-container">
              <div class="product">
                <p class="title">产品</p>
                <div class="list-left">
                  <a href="#" class="link-wrapper">
                    <span class="icon-wsc"></span>
                    <h4>有赞微商城</h4>
                    <p>网上开店工具，帮你提升销量</p>
                  </a>
                  <a href="#" class="link-wrapper">
                    <span class="icon-meiye"></span>
                    <h4>有赞美业</h4>
                    <p>轻松拉新客，快乐管店务</p>
                  </a>
                  <a href="#" class="link-wrapper">
                    <span class="icon-pay"></span>
                    <h4>有赞收银</h4>
                    <p>功能强大的线下收银系统</p>
                  </a>
                  <a href="#" class="link-wrapper">
                    <span class="icon-pf"></span>
                    <h4>有赞批发</h4>
                    <p>连接进货商和批发市场</p>
                  </a>
                </div>
                <div class="list-left">
                  <a href="#" class="link-wrapper">
                    <span class="icon-ls"></span>
                    <h4>有赞零售</h4>
                    <p>打通门店网店，业绩翻倍增长</p>
                  </a>
                  <a href="#" class="link-wrapper">
                    <span class="icon-cy"></span>
                    <h4>有赞餐饮</h4>
                    <p>堂食、外卖，统一高效管理</p>
                  </a>
                  <a href="#" class="link-wrapper">
                    <span class="icon-hy"></span>
                    <h4>有赞会议</h4>
                    <p>一站式全流程会务解决方案</p>
                  </a>
                  <a href="#" class="link-wrapper">
                    <span class="icon-wxd"></span>
                    <h4>有赞微小店</h4>
                    <p>手机开店神器，没货也能开店</p>
                  </a>
                </div>
              </div>
              <div class="product">
                <div class="list-right">
                  <p class="title"></p>
                  <a href="#">
                    <h4>分销</h4>
                    <p>搭建分销网络，万人帮你卖货</p>
                  </a>
                  <a href="#">
                    <h4>票务</h4>
                    <p>在线售票，快速核销，提升营收能力</p>
                  </a>
                  <a href="#">
                    <h4>媒体</h4>
                    <p>快速拥有网店，微信粉丝变现</p>
                  </a>
                  <a href="#">
                    <h4>广告投放</h4>
                    <p>连接优质流量，获取目标客户</p>
                  </a>
                </div>
                <div class="list-right">
                  <p class="title">解决方案</p>
                  <a href="#">
                    <h4>小程序</h4>
                    <p>一键接入，抢占市场红利</p>
                  </a>
                  <a href="#">
                    <h4>酒店</h4>
                    <p>满足订房、餐饮、娱乐等多场景</p>
                  </a>
                  <a href="#">
                    <h4>App开店</h4>
                    <p>让每个App都拥有强大的商城能力</p>
                  </a>
                  <a href="#">
                    <h4>定制服务</h4>
                    <p>一站式产品定制开发及服务定制策划</p>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </li>
        <li>
          <a href="#">有赞云</a>
        </li>
        <li>
          <a href="#">渠道合作</a>
        </li>
        <li class="dropdown">
          <a href="javascript:;">服务资源</a>
          <div class="arrow">
             <svg class="icon" aria-hidden="true">
              <use xlink:href="#icon-arrowdown"></use>
            </svg>
          </div>
          <div class="dropdown-menu">
            <div class="dropdown-menu-container">
              <a class="item-product">
                <h4>商家社区</h4>
                <p>有赞商家在线交流社区</p>
              </a>
               <a class="item-product">
                <h4>服务支持</h4>
                <p>专属服务经理对接商家</p>
              </a>
               <a class="item-product">
                <h4>有赞学院</h4>
                <p>视频教学让学习更简单</p>
              </a>
               <a class="item-product">
                <h4>有赞商盟</h4>
                <p>地方商圈资源合作分享</p>
              </a>
            </div>
            <div class="bottom-contact">
                <span class="tel">开店咨询：0571 - 8522 5188   商家服务：0571 - 8998 8848</span>
                <span class="pipe">|</span>
                <span class="time">周一到周日 9:00 ~ 18:00</span>
            </div>
          </div>
        </li>
        <li class="login-btn">
          <a href="#">登录</a>
        </li>
        <li class="register-btn">
          <a href="#">注册</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
if (process.BROWSER_BUILD) {
  require('~/assets/js/iconfont.js')
}

export default {

}
</script>

<style lang="scss">
  @import "../../assets/scss/variable.scss";
  @import "../../assets/scss/mixin.scss";

  .header {
    min-width: 1100px;
    border-bottom: 1px solid #ededed;
    position: relative;
    .header-container {
      @include clearfix;
      width: 1100px;
      height: $header-height;
      margin: 0 auto;
      .logo {
        display: inline-block;
        background-image: url('~/assets/images/logo.png');
        width: 72px;
        height: 25px;
        background-size: 72px 25px;
        margin-top: 22.5px;
      }
      .nav {
        @include clearfix;
        float: right;
        li {
          float: left;
          height: $header-height;
          line-height: $header-height;
          padding: 0 25px;
          cursor: pointer;
          &:not(.login-btn):not(.register-btn):not(.dropdown):hover {
            a {
              color: $header-hover-color;
            }
          }
          a {
            color: $header-default-color;
            font-size: 14px;
            margin-right: 15px;
          }
        }
        .dropdown {
          &:hover {
            a {
              color: $header-hover-color;
            }
            .arrow {
              .icon {
                color: $header-hover-color;
              }
            }
            .dropdown-menu {
              max-height: 1000px;
              transform-origin: 50% 0;
              transform: rotate3d(0, 0, 0, 0deg);
            }
          }
          .dropdown-menu {
            position: absolute;
            max-height: 0;
            z-index: 1000;
            overflow: hidden;
            left: 0;
            transform: rotate3d(1, 0, 0, -90deg);
            box-shadow: inset 0 2px 5px rgba(0, 0, 0, 0.07);
            transform-origin: 50% 0;
            transition: 300ms ease-in-out;
            width: 100%;
            .dropdown-menu-container {
              margin: 30px auto;
              width: 100%;
              max-width: 1100px;
              line-height: 1;
              @include clearfix;
              .product {
                width: 50%;
                float: left;
                @include clearfix;
                &:first-child {
                  border-right: 0.5px solid #e5e5e5;
                }
                .title {
                  padding-left: 10px;
                  margin-bottom: 12px;
                  color: #666;
                  font-size: 12px;
                }
                .list-left {
                  float: left;
                  width: 50%;
                  .link-wrapper {
                    display: block;
                    width: 212px;
                    height: 70px;
                    padding: 13px 10px;
                    line-height: normal;
                    position: relative;
                    span {
                      width: 20px;
                      height: 20px;
                      position: absolute;
                      top: 13px;
                      left: 10px;
                      background-position: center;
                      background-size: cover;
                      &.icon-wsc {
                        background-image: url('~/assets/images/icon-wsc@2x.png');
                      }
                      &.icon-meiye {
                        background-image: url('~/assets/images/icon-meiye@2x.png');
                      }
                      &.icon-pay {
                        background-image: url('~/assets/images/icon-pay@2x.png');
                      }
                      &.icon-pf {
                        background-image: url('~/assets/images/icon-pf@2x.png');
                      }
                      &.icon-ls {
                        background-image: url('~/assets/images/icon-ls@2x.png');
                      }
                      &.icon-cy {
                        background-image: url('~/assets/images/icon-cy@2x.png');
                      }
                      &.icon-hy {
                        background-image: url('~/assets/images/icon-hy@2x.png');
                      }
                      &.icon-wxd {
                        background-image: url('~/assets/images/icon-wxd@2x.png');
                      }
                    }
                    h4 {
                      font-size: 16px;
                      color: #333;
                      margin-left: 26px;
                    }
                    p {
                      font-size: 12px;
                      color: #999;
                      margin-top: 5px;
                      margin-left: 26px;
                    }
                  }
                }
                .list-right {
                  float: right;
                  width: 50%;
                  @include clearfix;
                  .title {
                    width: 212px;
                    height: 18px;
                    float: right;
                    padding-left: 10px;
                  }
                  a {
                    display: block;
                    width: 212px;
                    height: 70px;
                    padding: 13px 10px;
                    margin-right: 0;
                    float: right;
                    h4 {
                      font-size: 16px;
                      color: #333;
                    }
                    p {
                      font-size: 12px;
                      color: #999;
                      margin-top: 5px;
                    }
                  }
                }
              }
              .item-product {
                float: left;
                margin-left: 46.6px;
                margin-right: 0;
                width: 240px;
                height: 80px;
                &:first-child {
                  margin-left: 0;
                }
                &:hover {
                   background: #f8f8f8;
                }
                h4 {
                  padding: 16px 0 10px 20px;
                  font-size: 16px;
                  line-height: normal;
                  color: #333;
                }
                p {
                  font-size: 12px;
                  line-height: 1;
                  color: #999;
                  padding-left: 20px;
                }
              }
            }
            .bottom-contact {
              margin: 0 auto;
              width: 1100px;
              border-top: 1px solid #e5e5e5;
              text-align: center;
              font-size: 12px;
              line-height: 30px;
              padding: 20px 0;
              color: #666;
              .pipe {
                padding: 0 20px;
              }
            }
          }
          .arrow {
            display: inline-block;
            position: relative;
            .icon {
              position: absolute;
              top: -10px;
              left: -12px;
              width: 10px;
              height: 10px;
              vertical-align: top;
              color: $header-default-color;
              fill: currentColor;
              overflow: hidden;
            }
          }
        }
        .login-btn {
          cursor: auto;
          padding: 0 0 0 25px;
          a {
            width: 80px;
            height: 30px;
            line-height: 28px;
            display: inline-block;
            border: 1px solid $header-btn-blue;
            color: $header-btn-blue;
            text-align: center;
            border-radius: 2px;
            &:hover {
              background: $header-btn-blue;
              color: #fff;
            }
          }
        }
        .register-btn {
          cursor: auto;
          padding: 0 0 0 10px;
          a {
            width: 80px;
            height: 30px;
            line-height: 30px;
            display: inline-block;
            color: #fff;
            text-align: center;
            border-radius: 2px;
            background: $header-btn-blue;
            &:hover {
              background: #5CB0FD;
            }
          }
        }
      }
    }
  }
</style>
