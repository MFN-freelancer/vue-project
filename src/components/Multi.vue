<template>
  <div>
    <section class="main-steps-part">
      <div class="container">
        <div id="wizard">
          <h2>First Step</h2>
          <section class="s1 d-flex">
            <div class="w-50 pr-40">
              <h3 class="ds">Step 1</h3>
              <h2>Welcome! Select your<br>
                meeting session time.</h2>
              <p class="mb-80">We implement our vision of automation ‘cross-platform’.
                Follow the short steps and we’ll talk soon.</p>
              <div class="d-flex flex-wrap minute-btn">
                <router-link to="#" id="go-next" class="btn-1 mr-40">15 minute meeting<img src="static/images/arrow.png"
                    class="ds"><img src="static/images/arrow-white.png" class="mb" width="20"></router-link>
                <router-link to="#" id="go-next01" class="btn-1">30 minute meeting<img src="static/images/arrow.png" class="ds"><img
                    src="static/images/arrow-white.png" class="mb" width="20"></router-link>
              </div>
            </div>
            <div class="w-50 text-center s1-img">
              <img src="static/images/img2.png" alt="" title="">

            </div>
          </section>
          <h2>Second Step</h2>
          <section class="s1 d-flex">
            <div class="w-50 pr-40">
              <h3 class="ds">Step 2</h3>
              <h2 class="mb-80">Select a Date & Time</h2>
              <div class="d-flex flex-wrap">
                <div class="mr-40 datepicker-main">
                  <p>Date: <div id="datepicker" class="mb-20"></div>
                    <div class="d-flex align-center flex-wrap mb-30"><img src="static/images/world.png" alt=""
                        class="mr-10"><span>Israel Time</span></div>
                </div>
                <div class="">
                  <h4 class="text-center mb mb-30">You’ve selected:<span class="primary-color"> Thursday, April
                      30</span></h4>
                  <span class="mb-20 d-flex ds">Thursday, April 30</span>
                  <ul class="time-select">
                    <li><router-link to="#" class="btn-1 time " id="go-next1">10:00<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">10:00<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">10:15<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">10:30<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">10:45<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">11:00<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">11:15<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">11:30<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">11:45<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                    <li><router-link to="#" class="btn-1 time">12:00<img src="static/images/arrow.png" class="ds"><img
                          src="static/images/arrow-white.png" class="mb" width="20"></router-link></li>
                  </ul>
                </div>
              </div>

            </div>
            <div class="w-50 text-center s1-img select-date-img">
              <img src="static/images/img3.png" alt="" title="">
            </div>
          </section>
          <h2>3rd Step</h2>
          <section class="s1 d-flex reverse-mb">
            <div class="w-60 pr-40">
              <h3 class="ds">Step 3</h3>
              <h2 class="mb-80">Personal Info</h2>
              <p class="mb-50">We promise to protect your personal information<br>
                in line with the most stringent policies and procedures.</p>
              <div class="personal-info">
                <form action="">
                  <ul class="flex-wrap d-flex">
                    <li class="input-grp w-50 mb-50">
                      <div><input class="custom-input w-100" type="text" placeholder="First Name (required) "></div>
                    </li>
                    <li class="input-grp w-50 mb-50">
                      <div><input class="custom-input w-100" type="text" placeholder="Last Name (required)  "></div>
                    </li>
                    <li class="input-grp w-50 mb-50 d-flex">
                      <div class="pre w-30">
                        <select name="" id="" class="custom-input w-100">
                          <option value="">+1</option>
                          <option value="">+1</option>
                        </select>
                      </div>
                      <div class="w-70">
                        <input class="custom-input w-100" type="text" placeholder="Phone (required) ">
                      </div>
                    </li>
                    <li class="input-grp w-50 mb-50">
                      <div><input class="custom-input w-100" type="text" placeholder="Email (required)  "></div>
                    </li>

                  </ul>
                  <div class="text-left">
                    <input type="checkbox" class="custom-check" id="id1">
                    <label for="id1" class="custom-label">Would you like to receive a price proposal?</label>
                  </div>
                  <div class="mb-80 text-left">
                    <input type="checkbox" class="custom-check" id="id2">
                    <label for="id2" class="custom-label">Click here to receive a cashier demo</label>
                  </div>
                  <div class="next-wrap">
                    <router-link to="#" id="go-next2" class="btn">Next</router-link>
                  </div>
                </form>
              </div>

            </div>
            <div class="w-40 text-center s1-img select-date-img">
              <img src="static/images/img4.png" alt="" title="">
            </div>
          </section>
          <h2>4th Step</h2>
          <section class="s1">
            <div class="d-flex flex-wrap reverse-mb w-100">
              <div class="w-60 pr-40">
                <h3 class="ds">Step 4</h3>
                <h2 class="mb-80">Payment Solution</h2>
                <p class="mb-50">Which Payment Solutions do you require? <br>
                  <span class="orange">(you can select multiple regions)</span></p>


              </div>
              <div class="w-40 text-center s1-img select-date-img">
                <img src="static/images/img5.png" alt="" title="">
              </div>
            </div>
            <div class="w-100">
              <div class="ped-form">
                <form action="">
                  <ul class="flex-wrap d-flex mb-50">
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id3">
                        <label for="id3" class="custom-label"><span>Credit Cards <img src="static/images/info.png" alt="">
                          </span></label>
                      </div>
                    </li>
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id10">
                        <label for="id10" class="custom-label"><span>EU <img src="static/images/EU.png" alt=""><img
                              src="static/images/info.png" alt="">
                          </span></label>
                      </div>
                    </li>
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id4">
                        <label for="id4" class="custom-label"><span>SEA <img src="static/images/sea.png"><img
                              src="static/images/info.png" alt=""> </span></label>
                      </div>
                    </li>
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id5">
                        <label for="id5" class="custom-label"><span>China <img src="static/images/china.png" alt=""><img
                              src="static/images/info.png" alt=""> </span></label>
                      </div>
                    </li>
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id6">
                        <label for="id6" class="custom-label"><span>Japan <img src="static/images/japan.png" alt=""><img
                              src="static/images/info.png" alt=""> </span></label>
                      </div>
                    </li>
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id7">
                        <label for="id7" class="custom-label"><span>Africa <img src="static/images/africa.png"><img
                              src="static/images/info.png" alt=""> </span></label>
                      </div>
                    </li>
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id8">
                        <label for="id8" class="custom-label"><span>Russia <img src="static/images/rs.png" alt=""><img
                              src="static/images/info.png" alt=""> </span></label>
                      </div>
                    </li>
                    <li>
                      <div class="card-item">
                        <input type="radio" name="cnt" class="custom-check" id="id9">
                        <label for="id9" class="custom-label"><span>LATAM <img src="static/images/LATAM.png" alt=""><img
                              src="static/images/info.png" alt=""> </span></label>
                      </div>
                    </li>


                  </ul>
                  <div class="next-wrap">
                    <router-link to="#" id="go-next3" class="btn">Next</router-link>
                  </div>
                </form>
              </div>
            </div>
          </section>
          <h2>5th Step</h2>
          <section class="s1 ">
            <div class="d-flex flex-wrap reverse-mb w-10`0">
              <div class="w-60 pr-40">
                <h3 class="ds">Step 5</h3>
                <h2 class="mb-80">Your Industry & Company</h2>
                <p class="mb-50">WChoose your industry.<br>
                  Please provide us with a few more details.</p>
              </div>
              <div class="w-40 text-center s1-img select-date-img">
                <img src="static/images/img6.png" alt="" title="">
              </div>
            </div>
            <div class="w-100">
              <div class="personal-info">
                <form action="">
                  <ul class="flex-wrap d-flex">
                    <li class="input-grp w-30 mb-50">
                      <div><select name="" id="" class="custom-input w-100">
                          <option value="">Industry</option>
                          <option value="">Industry 1</option>
                        </select></div>
                    </li>
                    <li class="input-grp w-30 mb-50">
                      <div><select name="" id="" class="custom-input w-100">
                          <option value="">Sub Industry</option>
                          <option value="">Sub Industry 1</option>
                        </select></div>
                    </li>
                    <li class="input-grp w-30 mb-50">
                      <div><select name="" id="" class="custom-input w-100">
                          <option value="">Volume</option>
                          <option value="">Volume 1</option>
                        </select></div>
                    </li>
                    <li class="input-grp w-30 mb-50">
                      <div><input type="text" class="custom-input w-100" placeholder="URL (www.example.com)"></div>
                    </li>
                    <li class="input-grp w-30 mb-50">
                      <div><select name="" id="" class="custom-input w-100">
                          <option value="">Country</option>
                          <option value="">Country 1 </option>
                        </select></div>
                    </li>
                    <li class="input-grp w-50 mb-50">
                      <div><textarea class="custom-input w-100" name="" id="" cols="30" rows="10"
                          placeholder="Comments"></textarea></div>
                    </li>
                    <li class="input-grp w-30 mb-50">
                      <div class="">
                        <h3 class="primary-color  mb-0">Thursday, April 30, 2020
                          10:15 - 10:30</h3>
                        <div class="d-flex align-center flex-wrap mb-30 mb-jus-center"><img src="static/images/world.png"
                            alt="" class="mr-10"><span>Israel Time</span></div>
                        <div class="w-100">
                          <router-link to="/thank" class="btn">Schedule the Meeting</router-link>
                        </div>
                      </div>
                    </li>

                  </ul>

                </form>
              </div>
            </div>
          </section>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  name: 'Home',
  mounted() {
    const stepScript = document.createElement('script');
    stepScript.setAttribute('src', '../../../static/js/jquery-steps.js');
    document.head.appendChild(stepScript);

    const uiScript = document.createElement('script');
    uiScript.setAttribute('src', '../../../static/js/jquery-ui.js');
    document.head.appendChild(uiScript);

    $("#wizard").steps({
                headerTag: "h2",
                bodyTag: "section",
                transitionEffect: "slideLeft",
                stepsOrientation: "vertical",
                enablePagination:true,
                startIndex: 0,
            });
            $(function () {
                $("#datepicker").datepicker().show();
            });
            $(".humberg-menu").click(function(){
                $("header nav").toggleClass("show-nav");
                $(this).toggleClass("change-menu");
            });
            $('#go-next').click(function(){
                $('a[href="#next"]').trigger('click');
            });
            $('#go-next01').click(function(){
                $('a[href="#next"]').trigger('click');
            });
            $('#go-next1').click(function(){
                $('a[href="#next"]').trigger('click');
            });
            $('#go-next2').click(function(){
                $('a[href="#next"]').trigger('click');
            });
            $('#go-next3').click(function(){
                $('a[href="#next"]').trigger('click');
            });
            $('.time').click(function(){
                $('a[href="#next"]').trigger('click');
            });
  }
}
</script>
<style scoped>

</style>