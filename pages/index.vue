<template>
  <div>
    <nav class="navbar navbar-expand-md border-bottom shadow-sm">
      <div class="container">
        <a href="#" class="navbar-brand"><b>日新研修</b></a>
        <button class="navbar-toggler" tye="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav mr-auto">
            <li class="navbar-item active">
              <a href="#" class="nav-link">ホーム</a>
            </li>
          </ul>
          <ul class="navbar-nav text-light">
            <li class="navbar-item active">
              <a href="#" class="btn btn-outline-primary">ログイン</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container mt-4">
      <h1 class="display-4 mb-4 text-center jp-font">修了証明書</h1>
      <h4 class="jp-font text-center mb-4">
        日新研修コースを修了した対象者に対して、修了証明書を提供するサイト
      </h4>

      <div class="row mb-4">
        <div class="col-4">
          <div class="card border-primary">
            <div class="card-body">
              <h5 class="card-title">スマートコントラクト開発</h5>
              <p class="card-text">
                <ul class="list-group light-group-flush">
                  <li class="list-group-item">
                    日程
                    <div class="float-right">
                      <span class="badge badge-primary">2018/06/30 ~ 2018/07/31</span>
                    </div>
                  </li>
                  <li class="list-group-item">
                    クラス
                    <div class="float-right">
                      <span class="badge badge-primary">基礎</span>
                    </div>
                  </li>
                  <li class="list-group-item">
                    言語
                    <div class="float-right">
                      <span class="badge badge-primary">中国語</span>
                    </div>
                  </li>
                </ul>
              </p>
            </div>
            <div class="card-footer">
              <span>
                <i class="fa fa-users"></i>
                15 人
              </span>
              <span class='ml-4'>
                <i class="fa fa-clock"></i>
                12 時間
              </span>
              <a href="#" class="btn btn-primary btn-sm float-right">詳細</a>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">スマートコントラクト開発</h5>
              <p class="card-text">
                <ul class="list-group light-group-flush">
                  <li class="list-group-item">
                    日程
                    <div class="float-right">
                      <span class="badge badge-primary badge-pill">未定</span>
                    </div>
                  </li>
                  <li class="list-group-item">
                    クラス
                    <div class="float-right">
                      <span class="badge badge-primary badge-pill">上級</span>
                    </div>
                  </li>
                  <li class="list-group-item">
                    言語
                    <div class="float-right">
                      <span class="badge badge-primary badge-pill">中国語</span>
                    </div>
                  </li>
                </ul>
              </p>
            </div>
            <div class="card-footer">
              <span>
                <i class="fa fa-users"></i>
                最大 20 人
              </span>
              <span class='ml-4'>
                <i class="fa fa-clock"></i>
                12 時間
              </span>
              <a href="#" class="btn btn-outline-primary disabled btn-sm float-right">未定</a>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">スマートコントラクト開発</h5>
              <p class="card-text">
                <ul class="list-group light-group-flush">
                  <li class="list-group-item">
                    日程
                    <div class="float-right">
                      <span class="badge badge-primary badge-pill">2018/09/29 ~ 2018/10/07</span>
                    </div>
                  </li>
                  <li class="list-group-item">
                    クラス
                    <div class="float-right">
                      <span class="badge badge-primary badge-pill">基礎</span>
                    </div>
                  </li>
                  <li class="list-group-item">
                    言語
                    <div class="float-right">
                      <span class="badge badge-primary badge-pill">日本語</span>
                    </div>
                  </li>
                </ul>
              </p>
            </div>
            <div class="card-footer">
              <span>
                <i class="fa fa-users"></i>
                12 人
              </span>
              <span class='ml-4'>
                <i class="fa fa-clock"></i>
                12 時間
              </span>
              <a href="#" class="btn btn-outline-primary disabled btn-sm float-right">進行中</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="mt-4 pt-4 text-center">
      <div class="container border-top pt-3">
        Copyright © 2018 · <a href="#"><b>NisSin 日新株式会社</b></a>
      </div>
    </footer>
  </div>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style lang='scss'>
.logo {
  img {
    width: 100px;
  }
}

.single-widget {

}

</style>
