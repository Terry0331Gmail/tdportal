<template>
  <div>

    <header id="slider-area">
      
      <nav class="navbar navbar-expand-md fixed-top  scrolling-navbar bg-white menu-bg">
        <div class="container">
          <img src='@/assets/images/logo.png' style="width:100px">
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
            <i class="lni-menu"></i>
          </button>
          <div class="collapse navbar-collapse" id="navbarCollapse">
            <ul class="navbar-nav mr-auto w-100 justify-content-end">
              <li class="nav-item">
                <a class="nav-link page-scroll" href="#intro">計畫簡介</a>
              </li>
              <li class="nav-item">
                <a class="nav-link page-scroll" href="#object">計畫目標</a>
              </li>
              <li class="nav-item">
                <a class="nav-link page-scroll" href="#plan">分項計畫</a>
              </li>
              <li class="nav-item">
                <a class="nav-link page-scroll" href="#portfolios">活動照片</a>
              </li>
              <li class="nav-item">
                <a class="nav-link page-scroll" href="#teams">研究團隊</a>
              </li>


            </ul>
          </div>
        </div>
      </nav>

      <div class="container">

        <div class="row" style="margin-top:20px;">
          <div class="col-lg-12 col-md-12 col-xs-12">
            <img ref="responsiveImage" src="@/assets/img/home/pg_1.png" alt="" usemap="#image-map" style="max-width:1082px;width:100%" @load="adjustCoords">
            <map name="image-map">
              <!-- 上半部分 -->
              <area shape="rect" coords="185,92,479,228" href="https://www.xraihealth.com" alt="Area 1">
              <!-- 下半部分三等分 -->
              <area shape="rect" coords="588,92,885,230" href="https://www.xraihealth.com" alt="Area 2">
              <area shape="rect" coords="185,265,481,439" href="https://tdportals.azurewebsites.net/public/home" alt="Area 3">
              <area shape="rect" coords="588,269,885,439" href="https://nthuportal.azurewebsites.net/" alt="Area 4">
            </map>
          </div>


        </div>
        <!-- Main Carousel Section -->

      </div>
    </header>
    <!-- Header Section End -->
    <section id="intro" class="section">
      <div class="container">

        <div class="section-header">
          <div class="section-title">
            ▌&nbsp;&nbsp;<font style="color: rgb(144, 153, 147);">計劃簡介</font>&nbsp;&nbsp;▌
            <span>Introduction</span>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-6 col-md-6 col-xs-12">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <iframe width="100%" height="315" src="https://www.youtube.com/embed/a4UGHgpkhdk?si=4-L2gN9Qwp9Qp6Z1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12">
            <div class="services-item wow fadeInDown" data-wow-delay="0.4s" style="text-align:left">

              <p style="font-weight:normal;text-align:left">
                發展遲緩兒童的早期療育，0-6歲的黃金療育期，可大幅減輕社會照護負擔。療育過程最重要的是精準的全方面評估、充足的個別化療育訓練以及家庭能力的涵養。然偏鄉地區面臨專業養成與可供性的不足、設備資源可近性的困境、家庭社會資本缺乏，導致無法滿足上述需求，再加上新冠病毒大流行，亦影響著當前整體早療專
                業的輸出。本計劃核心精神為藉由科技創新與跨領域整合，解決當前早療痛點，尤
                其是偏鄉區域；以人本化的人工智慧科技，回應偏鄉早療問題及迫切需求，提出有
                溫度的科技解決方案。本計劃擬整合資訊科技、特殊教育、臨床醫學、早期療育等
                多領域專家進行研發，將科技資源挹注偏鄉，以上述研發成果進行實際場域驗證測
                試，服務偏鄉人群。
                <br>

              </p>
            </div>
          </div>
        </div>

        <div class="row">
          <div class="col-lg-6 col-md-6 col-xs-12">
            <div class="item-boxes services-item wow fadeInDown" data-wow-delay="0.2s">
              <div class="icon color-1">
                <i class="lni-pencil"></i>
              </div>
              <h4><b>計畫背景</b></h4>
              <p style="font-weight: normal; text-align: left">
                早療專業發展是世界潮流，發展遲緩兒童越早療育越好，可大幅減輕社會的長期負擔。然而，現行的早療模式，尤其是對於地處偏鄉的發展遲緩兒童與身心障礙家庭，仍然存在下列亟待解決的問題：偏遠地區專業人力匱乏，交通不便，療育服務成本高昂，家庭參與與自主決策能力不足。本計畫整合跨領域專業，開發遠距早療平台，提供虛擬實境遊戲、家庭功能評估系統等工具，以人工智慧技術協助早期療育服務。透過此計畫，我們期望能夠有效解決偏鄉早療困境，提升早期療育品質，讓偏遠地區的發展遲緩兒童及其家庭能夠得到更好的支持與幫助。
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12">
            <div class="item-boxes services-item wow fadeInDown" data-wow-delay="0.4s">
              <div class="icon color-2">
                <i class="lni-cog"></i>
              </div>
              <h4><b>計畫目的與重要性</b></h4>
              <p style="font-weight: normal; text-align: left ">本計畫旨在運用科技創新與整合應用，解決偏遠地區早期療育的困境，以科技人本化的跨領域應用創新，提出解決偏鄉早療問題的科技解決方案。首先，建立物聯網技術平臺，實現早療資訊匯流，提升專業可及性。其次，利用人工智慧技術分析多模態資訊，推薦精準療育介入方案。再者，建立虛擬實境技術自適應訓練系統，實現遠距早療復健。最後，結合機器學習推薦療育目標與介入方案，協助發展遲緩兒童家長提升自我決策能力。透過這些措施，期望能夠改善偏鄉早療的痛點，提升早期療育的品質，為發展遲緩兒童及其家庭帶來更多支持與幫助。</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12">
            <div class="item-boxes services-item wow fadeInDown" data-wow-delay="0.6s">
              <div class="icon color-3">
                <i class="lni-stats-up"></i>
              </div>
              <h4><b>研究方法</b></h4>
              <p style="font-weight: normal; text-align: left">
                本計畫以科技創新應對偏遠地區早期療育的挑戰，主要分為四個方面：<br>
                (1)整合早期療育與學前特殊教育評估資訊，為專業人及兒童家長員提供培訓輔助，提供個別化療育方案。<br>
                (2)建構虛擬實境復健遊戲室，協助兒童在進行認知或運動復健訓練。<br>
                (3)利用人工智慧建立早期療育目標評估與介入方案評估模型，實現自動化評估。<br>
                (4)運用人工智慧輔助家庭親子自我決策技能，為發展遲緩兒童及其家庭帶來更多支持與幫助。<br>
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12">
            <div class="item-boxes services-item wow fadeInDown" data-wow-delay="0.8s">
              <div class="icon color-4">
                <i class="lni-layers"></i>
              </div>
              <h4><b>計畫架構</b></h4>
              <p style="font-weight: normal; text-align: left">
                子計畫一：早療資訊匯流平台<br>
                (1) 家長端：家長可以適當的獲得早期介入相關的線上課程。<br>
                (2) 行政端：提供給早期介入相關的行政人員之管理系統。<br>
                (3) 專團端：提供給早期介入等專業人士相關的管理服務。<br>
                子計畫二：發展遲緩兒童復健虛擬遊戲室<br>
                子計畫三：發展遲緩兒童早期療育目標評估與介入方案人工智慧系統推薦系統<br>
                子計畫四：機器學習辨識結合特殊幼兒自我決策能力培訓<br>
              </p>
            </div>
          </div>


        </div>
      </div>
    </section>

    <!-- Features Section Start -->
    <section id="plan" class="section">
      <div class="container" data-ref="container-2">
        <div class="section-header">
          <div class="section-title">
            ▌&nbsp;&nbsp;<font style="color: rgb(144, 153, 147);">分項計畫</font>&nbsp;&nbsp;▌
            <span>Project Details</span>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <!-- Portfolio Controller/Buttons -->
            <div class="controls text-center">
              <a class="control btn btn-common btn-effect"  @click="scrollPage" data-filter=".pland1">計畫一</a>
              <a class="control btn btn-common btn-effect"  @click="scrollPage" data-filter=".pland2">計畫二</a>
              <a class="control btn btn-common btn-effect"  @click="scrollPage" data-filter=".pland3">計畫三</a>
              <a class="control btn btn-common btn-effect"  @click="scrollPage" data-filter=".pland4">計畫四</a>
            </div>
            <!-- Portfolio Controller/Buttons Ends-->
          </div>
        </div>

        <div class="row">
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland1">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pland1.png' style="width: 100%;">
              <p>子計畫一摘要</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland1">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl1.png' style="width: 100%;">
              <p>早療跨領域專業整合平台</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland1">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl1-4.png' style="width:100%">
              <p>
                即時早療 VR 實驗分析系統架構
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland1">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl1-2.png' style="width: 100%;">
              <p>
                現行上線系統架構
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland1">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl1-3.png' style="width:100%">
              <p>
                即時早療分析系統視覺化
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pland2.png' style="width: 100%;">
              <p>子計畫二摘要</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2.png' style="width:100%">
              <p>發展遲緩兒童復健虛擬遊戲架構</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-2.png' style="width:100%">
              <p>神經感測資訊與設備</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-3.png' style="width:100%">
              <p>
                虛擬實境認知訓練模組
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-4.png' style="width:100%">
              <p>
                粗大動作運動復健模組
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-5.png' style="width:100%">
              <p>精細動作運動復健模組</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-6.png' style="width:100%">
              <p>動作捕捉設備以及力反饋設備</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-7.png' style="width:100%">
              <p>自適應智慧訓練模式</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-8.png' style="width:100%">
              <p>
                自動化智慧評估模型的建立
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland2">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl2-9.png' style="width:100%">
              <p>混合模型架構</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland3">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pland3.png' style="width: 100%;">
              <p>子計畫三摘要</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland3">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl3.png' style="width:100%">
              <p>發展遲緩兒童早期療育目標評估與介入方案人工智慧系統架構</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland3">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl3-2.png' style="width:100%">
              <p>發展遲緩兒童早期療育目標評估與介入方案人工智慧系統流程</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland4">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pland4.png' style="width: 100%;">
              <p>子計畫四摘要</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland4">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl4.png' style="width:100%">
              <p>機器學習辨識結合特殊幼兒自我決策能力培訓計畫概念</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland4">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl4-1.png' style="width:100%">
              <p>
                機器學習辨識結合特殊幼兒自我決策能力培訓研究理論架構圖
              </p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-xs-12 mix pland4">
            <div class="services-item wow fadeInDown" data-wow-delay="0.2s">
              <img src='@/assets/img/home/pl4-2.png' style="width:100%">
              <p>機器學習辨識結合特殊幼兒自我決策能力培訓建置流程示意圖</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Features Section Start -->
    <section id="object" class="section">
      <div class="container">
        <div class="section-header">
          <div class="section-title">
            ▌&nbsp;&nbsp;<font style="color: rgb(144, 153, 147);">計畫目標</font>&nbsp;&nbsp;▌
            <span>Project goals</span>
          </div>

        </div>
        <div class="row">
          <table class="table table-striped">
            <thead>
              <tr>
                <th scope="col"></th>
                <th scope="col">短期目標</th>
                <th scope="col">中期目標</th>
                <th scope="col">長期目標</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th scope="row">子計畫一</th>
                <td>
                  物聯網早療資訊匯流平台整合
                </td>
                <td>
                  即時早療VR實驗分析系統
                </td>
                <td>
                  多租戶早療系統
                </td>

              </tr>
              <tr>
                <th scope="row">子計畫二</th>
                <td>
                  虛擬遊戲室研發
                </td>
                <td>
                  自適應模式研發
                </td>
                <td>
                  自動化智慧評估模型研發
                </td>
              </tr>
              <tr>
                <th scope="row">子計畫三</th>
                <td>
                  系統建置前置作業
                </td>
                <td>
                  AI模型建置及最佳化
                </td>
                <td>
                  實際投入應用
                </td>

              </tr>
              <tr>
                <th scope="row">子計畫四</th>
                <td>
                  系統建置前置作業
                </td>
                <td>
                  系統建置與優化

                </td>
                <td>
                  遠距離服務模式應用社會
                </td>

              </tr>
            </tbody>
          </table>

        </div>
      </div>
    </section>

    <!-- Features Section End -->
    <!-- Blog Section -->
    <section id="portfolios" class="section">
      <!-- Container Starts -->
      <div class="container" data-ref="container-3">
        <div class="section-header">
          <div class="section-title">
            ▌&nbsp;&nbsp;<font style="color: rgb(144, 153, 147);">活動照片</font>&nbsp;&nbsp;▌
            <span>Photo Gallery</span>

          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <!-- Portfolio Controller/Buttons -->
            <div class="controls text-center">
              <a class="control btn btn-common btn-effect active" @click="scrollPage" data-filter="all">All</a>
              <a class="control btn btn-common btn-effect" @click="scrollPage" data-filter=".plan1">計畫一</a>
              <a class="control btn btn-common btn-effect" @click="scrollPage" data-filter=".plan2">計畫二</a>
              <a class="control btn btn-common btn-effect" @click="scrollPage" data-filter=".plan3">計畫三</a>
              <a class="control btn btn-common btn-effect" @click="scrollPage" data-filter=".plan4">計畫四</a>
            </div>
            <!-- Portfolio Controller/Buttons Ends-->
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan1">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p1-1.png' style="width:100%">
              <p>服務成果：導入場域-醫院</p>
            </div>
          </div>


          <div class="col-lg-4 col-md-6 col-xs-12 mix plan1">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p1-2.png' style="width:100%">
              <p>服務成果：導入場域-台東</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan1">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p1-3.png' style="width:100%">
              <p>服務成果：導入場域-苗栗</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan1">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p1-4.png' style="width:100%">
              <p>服務成果：導入場域-新竹</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan2">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p2-1.png' style="width:100%">
              <p>成果統計</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan2">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p2-2.png' style="width:100%">
              <p>導入場域-醫院</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan2">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p2-3.png' style="width:100%">
              <p>導入場域-新竹</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan2">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p2-4.png' style="width:100%">
              <p>導入場域-台東</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan2">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p2-5.png' style="width:100%">
              <p>導入場域-苗栗</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan3">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p3-1.png' style="width:100%">
              <p>導入台東學前集中式特教班</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan3">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p3-2.png' style="width:100%">
              <p>導入台東早療社福團體-1</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan3">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p3-3.png' style="width:100%">
              <p>導入台東早療社福團體-2</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-1.png' style="width:100%">
              <p>自我決策-選擇想要穿的衣服</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-2.png' style="width:100%">
              <p>
                自我決策-情緒管理：分享玩具
              </p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-3.png' style="width:100%">
              <p>
                自我決策-活動參與：親子共讀
              </p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-4.png' style="width:100%">
              <p>導入場域:園所合作_1</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-5.png' style="width:100%">
              <p>導入場域:園所合作_2</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-6.png' style="width:100%">
              <p>導入場域:園所合作_3</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-7.png' style="width:100%">
              <p>親職影片拍攝</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-8.png' style="width:100%">
              <p>
                自我決策-活動參與：主動下廚
              </p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-9.png' style="width:100%">
              <p>自我決策-活動參與：藝術創作</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix plan4">
            <div class="services-item wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/p4-10.png' style="width:100%">
              <p>家長社群合作</p>
            </div>
          </div>
        </div>
      </div>
      <div id="teams" class="container" data-ref="container-1">
        <div class="section-header">
          <div class="section-title">
            ▌&nbsp;&nbsp;<font style="color: rgb(144, 153, 147);">研究團隊</font>&nbsp;&nbsp;▌
            <span>Research Team</span>

          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <!-- Portfolio Controller/Buttons -->
            <div class="controls text-center">
              <a class="control active btn btn-common btn-effect" @click="scrollPage" data-filter="all">All</a>
              <a class="control btn btn-common btn-effect" @click="scrollPage" data-filter=".school">學校</a>
              <a class="control btn btn-common btn-effect" @click="scrollPage" data-filter=".partner">醫院</a>
              <a class="control btn btn-common btn-effect" @click="scrollPage" data-filter=".ngo">機構</a>
            </div>
            <!-- Portfolio Controller/Buttons Ends-->
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4 col-md-6 col-xs-12 mix school">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/logo1.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix school">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/logo2.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix school">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/logo3.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix partner">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner1.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix partner" style="width:100%">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner2.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix partner">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner3.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix partner">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner4.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix partner">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner5.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix ngo">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner6.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix ngo">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner7.png' style="width:100%">
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-xs-12 mix ngo">
            <div style="margin-bottom:0px">
              <img src='@/assets/img/home/partner8.png' style="width:100%">
            </div>
          </div>

        </div>
        
        
        <div class="row" style="border:1px;margin-top:100px">
          <div class="col-lg-12 col-md-12 col-xs-12">
            <div class="wow fadeInDown" style="margin-bottom:0px" data-wow-delay="0.2s">
              <img src='@/assets/img/home/ilogo.png' style="height:100%">
            </div>
          </div>
        </div>

      </div>
    </section>
    <!-- blog Section End -->
    <br>
    <!-- Floating bar at the bottom -->
    <div class="footer fixed-bottom text-center p-2">
      <span id="gotop" onclick="window.scrollTo({top: 0, behavior: 'smooth'});" data-toggle="tooltip" class="gotop_pulic" data-placement="top" title="最上方" data-class="tooltip-custom">▲</span>
      <span id="gobottom" onclick="window.scrollTo({top: document.body.scrollHeight, behavior: 'smooth'});" data-toggle="tooltip" class="gotop_pulic" data-placement="top" title="最下方" data-class="tooltip-custom">▼</span>
    </div>
  </div>
</template>
<style scoped src="@/assets/css/bootstrap2.css">
</style>
<style scoped src="@/assets/css/line-icons.css">
</style>
<style scoped src="@/assets/css/animate.css">
</style>
<style scoped src="@/assets/css/owl.carousel.css">
</style>
<style scoped src="@/assets/css/owl.theme.css">
</style>
<style scoped src="@/assets/css/responsive.css">
</style>
<style scoped src="@/assets/css/main.css">
</style>

<style scoped>
  
    .container_fox {
        width: 100%;
        padding-right: 10px;
        padding-left: 10px;
        margin-right: auto;
        margin-left: auto;
    }


    
</style>
<style>

  .header {
    background-color: #479573;
    height:50px;
  }
  .footer {
    background-color: #479573;
  }

  .gotop_pulic {
    width: 32px; /* 設置寬度和高度相等以創建圓形按鈕 */
    height: 32px;
    border-radius: 50%; /* 設置圓形邊角 */
    background-color: #fff; /* 設置背景顏色為白色 */
    color: #479573; /* 設置文字顏色 */
    font-size: 14px;
    line-height: 32px; /* 設置文字垂直居中 */
    display: inline-block; /* 設置為行內元素，以使文字垂直居中 */
    text-align: center; /* 設置文字水平居中 */
    cursor: pointer; /* 添加游標樣式，讓它看起來像是可點擊的按鈕 */
    margin: 0 5px; /* 添加一些外邊距以分隔按鈕 */
  }

    .gotop_pulic:hover {
      background-color: #ccc; /* 添加懸停時的背景顏色 */
      color: #333; /* 添加懸停時的文字顏色 */
    }

  

</style>
<script>
  import { WOW } from 'wowjs'
  import mixitup from 'mixitup';
  import 'bootstrap'
  import $ from 'jquery';

  import 'bootstrap/dist/css/bootstrap.min.css'
    export default {
        data() {
            return {
                
                originalCoords: null // 原始坐標值
            };

        },
        async mounted() {
            //document.body.style.fontFamily = "'標楷體', 'Microsoft JhengHei', sans-serif";
            // 初始化 Bootstrap 的 JavaScript 功能
            $('.navbar-toggler').on('click', function () {
              $('.collapse').toggleClass('show');
            });
            this.$nextTick(() => {
                new WOW().init();
                this.getOriginalCoords(); // 獲取原始坐標值
                this.adjustCoords();
                window.addEventListener('resize', this.adjustCoords);
                var containerEl1 = document.querySelector('[data-ref="container-3"]');
                var containerEl2 = document.querySelector('[data-ref="container-2"]');
                var containerEl3 = document.querySelector('[data-ref="container-1"]');
                mixitup(containerEl1, {
                    controls: {
                        scope: 'local'
                    },
                    selectors: {
                        target: '.mix'
                    },
                    load: {
                        filter: '.plan1' // 設置預設的篩選器為 ".plan1"
                    }
                });
                 mixitup(containerEl2, {
                    controls: {
                        scope: 'local'
                    },
                    selectors: {
                        target: '.mix'
                    },
                    load: {
                        filter: '.pland1' // 設置預設的篩選器為 ".plan1"
                    }
                });
                mixitup(containerEl3, {
                    controls: {
                        scope: 'local'
                    },
                    selectors: {
                        target: '.mix'
                    }
                });
            })
            
            
            //var containerEl = document.querySelector('.container_fox');
            //var mixer = mixitup(containerEl);
            this.adjustCoords();
            
        },
        beforeDestroy() {
            window.removeEventListener('resize', this.adjustCoords);
        },
        async created() {
            
        },
        beforeRouteLeave(to, from, next) {
            // 在離開組件前清理 MixItUp 實例
            var containerEl = document.querySelector('[data-ref="container-1"]');
            
            if (containerEl.mixitup) {
                containerEl.mixitup('destroy');
            }
            var containerE2 = document.querySelector('[data-ref="container-2"]');
            if (containerE2.mixitup) {
                containerE2.mixitup('destroy');
            }
            var containerE3 = document.querySelector('[data-ref="container-3"]');
            if (containerE3.mixitup) {
                containerE3.mixitup('destroy');
            }
            next();
        },
        methods: {
            getOriginalCoords() {
                const areas = document.getElementsByTagName('area');
                this.originalCoords = [];
                for (let i = 0; i < areas.length; i++) {
                    this.originalCoords.push(areas[i].getAttribute('coords').split(','));
                }
            },
            adjustCoords() {
                const image = this.$refs.responsiveImage;
                if (image && this.originalCoords) {
                    const originalWidth = 1082; // 原始圖片的寬度
                    const originalHeight = 532; // 原始圖片的高度
                    const currentWidth = image.clientWidth; // 當前圖片的寬度
                    const currentHeight = image.clientHeight; // 當前圖片的高度

                    const ratioX = currentWidth / originalWidth;
                    const ratioY = currentHeight / originalHeight;

                    const areas = document.getElementsByTagName('area');
                    for (let i = 0; i < areas.length; i++) {
                        const coords = this.originalCoords[i].slice(); // 複製原始坐標值
                        for (let j = 0; j < coords.length; j++) {
                            coords[j] = Math.round(coords[j] * (j % 2 === 0 ? ratioX : ratioY));
                        }
                        areas[i].setAttribute('coords', coords.join(','));
                    }
                }
            },
            scrollPage() {
                // 向下捲動頁面
                window.scrollBy({
                    top: 1, // 向下滾動10像素
                    behavior: "auto" // 平滑捲動效果
                });

                // 延遲一段時間後再向上捲動頁面
                setTimeout(() => {
                    window.scrollBy({
                        top: -1, // 向上滾動10像素
                        behavior: "auto" // 平滑捲動效果
                    });
                }, 1000); // 在捲動完成後等待500毫秒再向上滾動，這個時間可以根據需要調整
            }
            
        }
    }
</script>
