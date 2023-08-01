<template>
  <div class="d-flex flex-lg-row flex-column pb-lg-5 pt-3 custom-margin-bottom">
    <div class="col-lg-5 col-12">
      <picture class="d-flex flex-row mt-lg-5 pe-lg-5 picture">
        <img src="../../src/assets/images/image1.png" class="img-fluid w-100" alt="image" />
      </picture>
    </div>
    <div class="col-lg-7 col-12">
      <div class="text-center mb-lg-4"><h2>SINGLE MASSAGE</h2></div>
      <div class="d-flex flex-row rounded-table">
        <div class="flex-fill massage-table">
          <div class="d-flex table-row header">
            <div class="col-3 table-cell">SINGLE</div>
            <div class="col-3 table-cell">% OFF</div>
            <div class="col-3 table-cell">60-MIN</div>
            <div class="col-3 table-cell">90-MIN</div>
          </div>
          <div class="d-flex table-row">
            <div class="col-3 table-cell">5 SESIONS</div>
            <div class="col-3 table-cell">15%</div>
            <div class="col-3 table-cell">1300 <sup>AED</sup></div>
            <div class="col-3 table-cell">2300 <sup>AED</sup></div>
          </div>
          <div class="d-flex table-row">
            <div class="col-3 table-cell">10 SESIONS</div>
            <div class="col-3 table-cell">25%</div>
            <div class="col-3 table-cell">1740 <sup>AED</sup></div>
            <div class="col-3 table-cell">3070 <sup>AED</sup></div>
          </div>
        </div>
      </div>
      <div class="text-center mt-5">
        <button type="button" class="btn green-button">Book</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.picture {
  margin-bottom: 20px;
}

.rounded-table {
  border-radius: 58px;
  -webkit-border-radius: 58px;
  -moz-border-radius: 58px;
  -khtml-border-radius: 58px;
  background: #ae8f7d;
  padding: 4px;
  overflow: hidden;

  @media screen and (max-width: 450px) {
    border-radius: 8px;
    -webkit-border-radius: 8px;
    -moz-border-radius: 8px;
    -khtml-border-radius: 8px;
  }
}

.custom-margin-bottom {
  margin-bottom: 70px;
}

.massage-table {
  color: #fff;
  text-transform: uppercase;
  font-size: 16px;
  background-color: #ae8f7d;
  font-weight: 800;
}

.massage-table .header .table-cell {
  background-color: #ae8f7d;
}

.massage-table .header .table-cell:first-child {
  border-radius: 58px 0px 0px 0px;
  @media screen and (max-width: 450px) {
    border-radius: 8px 0px 0px 0px;
  }
}

.massage-table .header .table-cell:last-child {
  border-radius: 0px 58px 0px 0px;
  @media screen and (max-width: 450px) {
    border-radius: 0px 8px 0px 0px;
  }
}

.massage-table .table-row:last-child .table-cell:first-child {
  border-radius: 0px 0px 0px 58px;
  @media screen and (max-width: 450px) {
    border-radius: 0px 0px 0px 8px;
  }
}

.massage-table .table-row:last-child .table-cell:last-child {
  border-radius: 0px 0px 58px 0px;
  @media screen and (max-width: 450px) {
    border-radius: 0px 0px 8px 0px;
  }
}

.massage-table .table-cell {
  border: 4px solid #ae8f7d;
  background: #2d423b;
  font-weight: 700;
  min-height: 137px;
  align-items: center;
  justify-content: center;
  display: flex;

  @media screen and (max-width: 450px) {
    min-height: 47px;
    font-size: 12px;
  }
}

.massage-table .header .table-cell {
  min-height: 117px;
  @media screen and (max-width: 450px) {
    min-height: 47px;
  }
}

.massage-table .table-cell {
  font-weight: 700;
  white-space: pre-wrap;
}
</style>
