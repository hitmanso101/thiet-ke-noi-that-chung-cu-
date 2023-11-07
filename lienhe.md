<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" />
<style>
    @media (max-width:767px) {
        .hidden-xs {
            display: none !important
        }
    }

    .hot-linkly {
        position: fixed;
        right: 0;
        top: 150px;
        z-index: 99
    }

    .hot-linkly .bic-load {
        align-items: center;
        background: transparent url("https://1.bp.blogspot.com/-uRoTfpNL3-o/XvnTAQ0nO5I/AAAAAAAANg4/feBsOzB2rfY1hY_6KQEdnNoS4rDX_aFtACLcBGAsYHQ/s1600/toolbar.png") no-repeat scroll 0 0/100% 100%;
        display: flex;
        flex-direction: column;
        padding: 61px 0;
        width: 52px
    }

    .hot-linkly .bic-load .bic-load-tem {
        margin-bottom: 10px;
        width: 40px;
        height: 40px
    }

    .hot-linkly .bic-load .bic-load-tem .loptop {
        background: #fff none repeat scroll 0 0;
        border-radius: 20px;
        display: block;
        height: 40px;
        font-size: 14px;
        text-align: center;
        width: 40px;
        background-repeat: no-repeat;
        background-position: center;
        transition: width 300ms ease-in 0ms;
        cursor: pointer;
        position: absolute;
        right: 6px;
        font-weight: bold;
        text-decoration: none;
        color: #82bb4e
    }

    .hot-linkly .bic-load .bic-load-tem .loptop.hotline:before {
        content: "\f2a0";
        font-family: "FontAwesome";
        font-size: 23px;
        position: absolute;
        left: 12px;
        top: -1px;
        font-weight: 400
    }

    .hot-linkly .bic-load .bic-load-tem .loptop.facebook:before {
        content: "\f09a";
        font-family: "FontAwesome";
        font-size: 23px;
        position: absolute;
        left: 11px;
        top: 0;
        font-weight: 400
    }

    .hot-linkly .bic-load .bic-load-tem .loptop.fanpage:before {
        content: "\f0e6";
        font-family: "FontAwesome";
        font-size: 23px;
        position: absolute;
        left: 11px;
        top: 0;
        font-weight: 400
    }

    .hot-linkly .bic-load .bic-load-tem .loptop.youtube:before {
        content: "\f167";
        font-family: "FontAwesome";
        font-size: 23px;
        position: absolute;
        left: 11px;
        top: 0;
        font-weight: 400
    }

    .hot-linkly .bic-load .bic-load-tem .loptop span {
        visibility: hidden;
        transition: steps(1, start) 300ms ease-in 0ms
    }

    .hot-linkly .bic-load .bic-load-tem .loptop:hover {
        width: auto;
        display: flex;
        align-items: center;
        white-space: nowrap;
        background-position: left 15px center;
        padding-left: 55px;
        box-shadow: 0 0 2px;
        padding-right: 30px
    }

    .hot-linkly .bic-load .bic-load-tem .loptop:hover span {
        visibility: visible
    }
</style>
<div class="hot-linkly hidden-xs">
    <div class="bic-load">
        <div class="bic-load-tem">
            <a class="loptop hotline" href="tel:123456789">
        <span>Hotline</span>
      </a>
        </div>
        <div class="bic-load-tem">
            <a target="_blank" class="loptop facebook" href="/">
        <span>Facebook</span>
      </a>
        </div>
        <div class="bic-load-tem">
            <a target="_blank" class="loptop fanpage" href="/">
        <span>Fanpage</span>
      </a>
        </div>
        <div class="bic-load-tem">
            <a target="_blank" class="loptop youtube" href="/">
        <span>Kênh Youtube</span>
      </a>
        </div>
    </div>
    <span class="show_hide"></span>
</div>
