<template>
  <div class="page-wrapper">
    <!-- Page Content -->
    <div class="content container-fluid">
      <div class="row justify-content-center">
        <div class="col-xl-10">
          <div class="card invoice-info-card">
            <div class="card-body">
              <div class="invoice-item invoice-item-one">
                <div class="row">
                  <div class="col-md-6">
                    <div class="invoice-logo">
                      <img src="@/assets/img/logo-dark.png" alt="logo" />
                    </div>
                    <div class="invoice-head">
                      <h2>Invoice</h2>
                      <p>Invoice Number : In983248782</p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="invoice-info">
                      <strong class="customer-text-one">Invoice From</strong>
                      <h6 class="invoice-name">Company Name</h6>
                      <p class="invoice-details">
                        9087484288 <br />
                        Address line 1, Address line 2<br />
                        Zip code ,City - Country
                      </p>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Invoice Item -->
              <div class="invoice-item invoice-item-two">
                <div class="row">
                  <div class="col-md-6">
                    <div class="invoice-info">
                      <strong class="customer-text-one">Billed to</strong>
                      <h6 class="invoice-name">Customer Name</h6>
                      <p class="invoice-details invoice-details-two">
                        9087484288 <br />
                        Address line 1, <br />
                        Address line 2 <br />
                        Zip code ,City - Country
                      </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="invoice-info invoice-info2">
                      <strong class="customer-text-one">Payment Details</strong>
                      <p class="invoice-details">
                        Debit Card <br />
                        XXXXXXXXXXXX-2541 <br />
                        HDFC Bank
                      </p>
                      <div class="invoice-item-box">
                        <p>Recurring : 15 Months</p>
                        <p class="mb-0">PO Number : 54515454</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <!-- /Invoice Item -->

              <!-- Invoice Item -->
              <div class="invoice-issues-box">
                <div class="row">
                  <div class="col-lg-4 col-md-4">
                    <div class="invoice-issues-date">
                      <p>Issue Date : 27 Jul 2022</p>
                    </div>
                  </div>
                  <div class="col-lg-4 col-md-4">
                    <div class="invoice-issues-date">
                      <p>Due Date : 27 Aug 2022</p>
                    </div>
                  </div>
                  <div class="col-lg-4 col-md-4">
                    <div class="invoice-issues-date">
                      <p>Due Amount : ₹ 1,54,22</p>
                    </div>
                  </div>
                </div>
              </div>
              <!-- /Invoice Item -->

              <!-- Invoice Item -->
              <div class="invoice-item invoice-table-wrap">
                <div class="row">
                  <div class="col-md-12">
                    <div class="table-responsive">
                      <table class="invoice-table table table-center mb-0">
                        <thead>
                          <tr>
                            <th>Description</th>
                            <th>Category</th>
                            <th>Rate/Item</th>
                            <th>Quantity</th>
                            <th>Discount (%)</th>
                            <th class="text-end">Amount</th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td>Dell Laptop</td>
                            <td>Laptop</td>
                            <td>$1,110</td>
                            <td>2</td>
                            <td>2%</td>
                            <td class="text-end">$400</td>
                          </tr>
                          <tr>
                            <td>HP Laptop</td>
                            <td>Laptop</td>
                            <td>$1,500</td>
                            <td>3</td>
                            <td>6%</td>
                            <td class="text-end">$3,000</td>
                          </tr>
                          <tr>
                            <td>Apple Ipad</td>
                            <td>Ipad</td>
                            <td>$11,500</td>
                            <td>1</td>
                            <td>10%</td>
                            <td class="text-end">$11,000</td>
                          </tr>
                        </tbody>
                      </table>
                    </div>
                  </div>
                </div>
              </div>
              <!-- /Invoice Item -->

              <div class="row align-items-center justify-content-center">
                <div class="col-lg-6 col-md-6">
                  <div class="invoice-terms">
                    <h6>Notes:</h6>
                    <p class="mb-0">Enter customer notes or any other details</p>
                  </div>
                  <div class="invoice-terms">
                    <h6>Terms and Conditions:</h6>
                    <p class="mb-0">Enter customer notes or any other details</p>
                  </div>
                </div>
                <div class="col-lg-6 col-md-6">
                  <div class="invoice-total-card">
                    <div class="invoice-total-box">
                      <div class="invoice-total-inner">
                        <p>Taxable <span>$6,660.00</span></p>
                        <p>Additional Charges <span>$6,660.00</span></p>
                        <p>Discount <span>$3,300.00</span></p>
                        <p class="mb-0">Sub total <span>$3,300.00</span></p>
                      </div>
                      <div class="invoice-total-footer">
                        <h4>Total Amount <span>$143,300.00</span></h4>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="invoice-sign text-end">
                <img
                  class="img-fluid d-inline-block"
                  src="@/assets/img/signature.png"
                  alt="sign"
                />
                <span class="d-block">Harristemp</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- /Page Content -->
  </div>
</template>
