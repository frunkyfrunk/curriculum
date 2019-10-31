<template>
  <div>
    <div class="container">
      <div class="row" ref="content">
        <div
          class="col-md-8 offset-md-2 wow fadeIn mb-3"
          data-wow-duration="2.5s"
          data-wow-delay="0s"
        >
          <div class="container">
            <div class="resume-title">
              <div style="display: inline-block;" class="fixh">
                <h2 data-v-b51266c0>Frank</h2>
                <h2 data-v-b51266c0>Verhagen</h2>
              </div>
              <div
                data-v-b51266c0
                class="fixh"
                style="
    display: inline-block;
    margin-top: -3px;
    position: absolute;"
              >
                <h6>
                  <i class="fas fa-phone"></i> 06-21833104
                </h6>
                <h6>
                  <i class="far fa-envelope"></i> verhagen.frank@gmail.com
                </h6>
                <h6>
                  <i class="fab fa-github"></i> FrankVerhagen
                </h6>
                <h6>
                  <i class="fas fa-globe"></i> Rotterdam
                </h6>
              </div>
              <img src="/profiel.jpg" width="150px" class="pull-right avatar rounded-circle" />
              <div class="resume-designation">
                <span class="border"></span>
                <span>Software Engineer</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-8 offset-md-2 wow fadeIn" data-wow-duration="2.5s" data-wow-delay="0s">
          <div class="container">
            <h2 class="pt-2">
              <i class="fa fa-user"></i> Over mij
            </h2>
            <hr class="title" />
            <p class="content">
              Ik zou mijzelf omschrijven als een nieuwsgierig persoon, die veel nadenkt maar soms ook erg in
              zichzelf gekeerd kan zijn. Mijn sterke kant is dat ik goed creatief kan denken, dit kost mij meestal
              weinig moeite. Ook kan ik goed dingen verwoorden in een tekst. Deze eigenschappen probeer ik te
              combineren met mijn beroep als software engineer.
            </p>
          </div>
        </div>
        <div class="col-md-4 offset-md-2 wow fadeIn" data-wow-duration="2.5s" data-wow-delay="0.4s">
          <div class="container">
            <h2 class="pt-2">
              <i class="fas fa-clipboard-list"></i> Professionele skills
            </h2>
            <hr class="title" />
            <ul class="skill-dots" id="skill-dots">
              <li class="skill">
                <span class="skill-title">Schrijfvaardigheid</span>
                <div class="skill-progress" data-score="9">
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa wow animated" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">Zelfstandigheid</span>
                <div class="skill-progress" data-score="8">
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active" style="visibility: visible;"></i>
                  <i class="fa wow animated" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">Creativiteit</span>
                <div class="skill-progress" data-score="9">
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">Teamwerk</span>
                <div class="skill-progress" data-score="7">
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa wow animated" style="visibility: visible;"></i>
                  <i class="fa wow animated" style="visibility: visible;"></i>
                  <i class="fa wow animated" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">Leiderschap</span>
                <div class="skill-progress" data-score="4">
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active wow" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-md-4 wow fadeIn righty" data-wow-duration="2.5s" data-wow-delay="0.4s">
          <div class="container">
            <h2 class="pt-2">
              <i class="fas fa-laptop-code"></i> Programmeerervaring
            </h2>
            <hr class="title" />
            <ul class="skill-dots" id="skill-dots">
              <li class="skill">
                <span class="skill-title">Typescript</span>
                <div class="skill-progress" data-score="9">
                  <i class="fa active blue" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active blue" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">Javascript / Node.JS</span>
                <div class="skill-progress" data-score="8">
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active green" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active green" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active blue" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active blue" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active blue" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">Vue.JS</span>
                <div class="skill-progress" data-score="4">
                  <i class="fa active green" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active green" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">C# / .NET</span>
                <div class="skill-progress" data-score="9">
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active green" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                </div>
              </li>
              <li class="skill">
                <span class="skill-title">Java / Android</span>
                <div class="skill-progress" data-score="7">
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa active purple" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible; animation-name: skills;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                  <i class="fa" style="visibility: visible;"></i>
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-md-8 offset-md-2">
          <div data-v-b51266c0 class="skill">
            <div class="container">
              <ul class="skill-dots" id="skill-dots">
                <li class="skill">
                  <span class="skill-title" style="width:141px;">Legenda ervaring</span>

                  <div class="skill-progress" style="padding-left:10px">
                    <i
                      class="fa active wow blue"
                      style="visibility: visible; animation-name: skills;"
                    ></i>
                    < 1 jaar geleden
                  </div>
                  <div class="skill-progress" style="padding-left:10px">
                    <i
                      class="fa active wow green"
                      style="visibility: visible; animation-name: skills;"
                    ></i>
                    1 - 2 jaren geleden
                  </div>
                  <div class="skill-progress" style="padding-left:10px">
                    <i
                      class="fa active wow purple"
                      style="visibility: visible; animation-name: skills;"
                    ></i>
                    > 2 jaar geleden
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-md-8 offset-md-2 wow fadeIn" data-wow-duration="2.5s" data-wow-delay="0.6s">
          <div class="container">
            <h2 class="pt-2">
              <i class="fa fa-graduation-cap"></i> Opleiding
            </h2>
            <hr class="title" />
            <!--first section-->
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center bottom d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  2014
                  <br />-
                  <br />2019
                </div>
              </div>
              <div class="col-6">
                <h5>Bachelor Informatica</h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed porttitor gravida aliquam. Morbi orci urna, iaculis in ligula et, posuere interdum lectus.</p>
              </div>
            </div>
            <!--path between 1-2-->
            <div class="row timeline">
              <div class="col-2">
                <div class="corner top-right"></div>
              </div>
              <div class="col-8">
                <div
                  data-v-b51266c0
                  class
                  style="
    height: 20px;
    border-bottom: 3px solid #ff4d57;
    width: 100%;
    position: relative;
"
                ></div>
              </div>
              <div class="col-2">
                <div class="corner left-bottom"></div>
              </div>
            </div>
            <!--second section-->
            <div class="row align-items-center justify-content-end how-it-works d-flex">
              <div class="col-6 text-right">
                <h5>Minor Security</h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed porttitor gravida aliquam. Morbi orci urna, iaculis in ligula et, posuere interdum lectus.</p>
              </div>
              <div
                class="col-2 text-center full d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  2018
                  <br />-
                  <br />2019
                </div>
              </div>
            </div>
            <!--path between 2-3-->
            <div class="row timeline">
              <div class="col-2">
                <div class="corner right-bottom"></div>
              </div>
              <div class="col-8">
                <div
                  data-v-b51266c0
                  class
                  style="
    height: 20px;
    border-bottom: 3px solid #ff4d57;
    width: 100%;
    position: relative;
"
                ></div>
              </div>
              <div class="col-2">
                <div class="corner top-left"></div>
              </div>
            </div>
            <!--third section-->
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center full-left d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  2014
                  <br />-
                  <br />2016
                </div>
              </div>
              <div class="col-6">
                <h5>Propedeuse Informatica</h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed porttitor gravida aliquam. Morbi orci urna, iaculis in ligula et, posuere interdum lectus.</p>
              </div>
            </div>
            <!--path between 3-4-->
            <div class="row timeline">
              <div class="col-2">
                <div class="corner top-right"></div>
              </div>
              <div class="col-8">
                <div
                  data-v-b51266c0
                  class
                  style="
    height: 20px;
    border-bottom: 3px solid #ff4d57;
    width: 100%;
    position: relative;
"
                ></div>
              </div>
              <div class="col-2">
                <div class="corner left-bottom"></div>
              </div>
            </div>
            <!--fourth section-->
            <div class="row align-items-center justify-content-end how-it-works d-flex">
              <div class="col-6 text-right">
                <h5>Havo</h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed porttitor gravida aliquam. Morbi orci urna, iaculis in ligula et, posuere interdum lectus.</p>
              </div>
              <div
                class="col-2 text-center full d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  2009
                  <br />-
                  <br />2014
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-8 offset-md-2 wow fadeIn" data-wow-duration="2.5s" data-wow-delay="0s">
          <div class="container">
            <h2 class="pt-2">
              <i class="fas fa-briefcase"></i> Werkervaring
            </h2>
            <hr class="title" />
            <!--first section-->
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  <br />2019
                </div>
              </div>
              <div class="col-10">
                <h5>App4mation - Afstudeerstage</h5>
                <p>Het onderwerp van mijn afstudeeropdracht was het onderzoeken hoe een IoT-platform kan worden geïntegreerd met ServiceNow, het cloudplatform dat App4mation gebruikt voor enterprise-applicaties. Hierbij moest ik rekening houden met de beperkingen van het ServiceNow-platform.</p>
              </div>
            </div>

            <!--second section-->
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  2017
                  <br />-
                  <br />2018
                </div>
              </div>
              <div class="col-10">
                <h5>Xylem Water Solutions - Stage</h5>
                <p>
                  Mijn stageopdracht was het doorontwikkelen van een webapplicatie voor klachtenregistratie die intern
                  gebruikt werd door medewerkers van de helpdesk.
                  De backend van de applicatie bestond uit een API draaiende op het ASP .NET (C#) framework. De
                  front-end is met Vue.js in componenten opgebouwd, en draait op een Node.js Webpack
                  serveromgeving.
                </p>
              </div>
            </div>
            <!--third section-->
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  2016
                  <br />-
                  <br />2017
                </div>
              </div>
              <div class="col-10">
                <h5>Studentaanhuis</h5>
                <p>
                  Hier gaf ik mensen computerhulp aan huis. Ik hielp bij diverse problemen met betrekking tot
                  computers, laptops en telefoon. Om de technologie toegankelijk te maken krijgt de klant uitleg als dat
                  nodig is.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-8 offset-md-2 wow fadeIn" data-wow-duration="2.5s" data-wow-delay="0.2s">
          <div class="container">
            <h2 class="pt-2">
              <i class="far fa-file"></i> Certificaten
            </h2>
            <hr class="title" />
            <!--first section-->
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center d-inline-flex justify-content-center align-items-center"
              >
                <div class="circle font-weight-bold">
                  <br />2018
                </div>
              </div>
              <div class="col-10">
                <h5>Professional Scrum Master I</h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed porttitor gravida aliquam. Morbi orci urna, iaculis in ligula et, posuere interdum lectus.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-8 offset-md-2 wow fadeIn" data-wow-duration="2.5s" data-wow-delay="0.2s">
          <div class="container">
            <h2 class="pt-2">
              <i class="fas fa-globe"></i> Talen
            </h2>
            <hr class="title" />
            <!--first section-->
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center d-inline-flex justify-content-center align-items-center"
              >Engels</div>
              <div class="col-10">
                <table class="table">
                  <thead>
                    <tr>
                      <th scope="col">Lezen</th>
                      <th scope="col">Schrijven</th>
                      <th scope="col">Luisteren</th>
                      <th scope="col">Praten</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>B2</td>
                      <td>B2</td>
                      <td>B1</td>
                      <td>B2</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
            <div class="row align-items-center how-it-works d-flex">
              <div
                class="col-2 text-center d-inline-flex justify-content-center align-items-center"
              >Nederlands</div>
              <div class="col-10">
                <table class="table">
                  <thead>
                    <tr>
                      <th scope="col">Lezen</th>
                      <th scope="col">Schrijven</th>
                      <th scope="col">Luisteren</th>
                      <th scope="col">Praten</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>B2</td>
                      <td>B2</td>
                      <td>B2</td>
                      <td>B2</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import jsPDF from "jspdf";
import html2canvas from "html2canvas";
export default {
  name: "AppHome"
};
new WOW().init();
</script>

<style scoped>
.blue {
  color: #2bb3f2 !important;
}
.green {
  color: #2bf253 !important;
}
.purple {
  color: #a22bf2 !important;
}
@media print {
  .container {
    margin-left: 15mm;
  }
  .righty {
    margin-left: 165px;
  }
  .fixh {
    width: 550px;
  }
}
.avatar {
  border: 4px solid #ff4d57;
  margin-top: -9px;
}
.resume-designation {
  margin-top: 4px;
  display: inline-block;
}
.resume-designation span.border {
  width: 100%;
  max-width: 290px;
  height: 4px;
  margin-right: 25px;
  border-style: none !important;
  background-color: #ff4d57;
}
.resume-designation span {
  display: inline-block;
  font-size: 14px;
  font-weight: 700;
  text-transform: uppercase;
  color: #1f1f29;
  letter-spacing: 0.5em;
  vertical-align: middle;
}
.resume-title h2 {
  font-size: 40px;
  font-weight: 800;
  text-transform: uppercase;
  color: #1f1f29;
  line-height: 0.69em;
  letter-spacing: 0.14em;
}
ul.skill {
  margin: 0px 0;
  list-style: none;
  overflow-x: hidden;
  padding-inline-start: 0px;
}
ul.skill li {
  max-width: 320px;
  margin-top: 15px;
  height: 48px;
  position: relative;
}
ul.skill li p {
  margin: 0;
  margin-bottom: 10px;
  font-size: 13px;
  font-weight: 400;
  letter-spacing: 1.2px;
  text-transform: uppercase;
  color: #1f1f29;
}
ul.skill li:before {
  width: 100%;
  height: 4px;
  content: "";
  display: block;
  position: absolute;
  background: #eeeeee;
  bottom: 0;
}
ul.skill li .skill-bar {
  width: 100%;
  height: 4px;
  background: #2e2828;
  display: block;
  position: relative;
}
ul.skill li .skill-bar .skill-tip {
  position: absolute;
  top: -27px;
  right: 0px;
  padding: 5px 10px;
  border-radius: 4px;
  font-size: 11px;
  font-weight: 400;
  line-height: 11px;
  background-color: #ff4d57;
  color: #fff;
}
ul.skill li .skill-bar .skill-tip:after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 50%;
  width: 0;
  height: 0;
  border: 6px solid transparent;
  border-top-color: #ff4d57;
  border-bottom: 0;
  margin-left: -6px;
  margin-bottom: -6px;
}
ul.skill-dots {
  padding-inline-start: 0px;
}
ul.skill-dots li {
  display: inline-block;
  margin-top: 15px;
  height: 48px;
  margin-bottom: 0px;
  width: 100%;
}
ul.skill-dots li .skill-title {
  display: inline-block;
  width: 185px;
  margin: 0;
  font-size: 13px;
  font-weight: 400;
  letter-spacing: 1.2px;
  text-transform: uppercase;
  color: #1f1f29;
}
ul.skill-dots li .skill-progress {
  display: inline-block;
}
ul.skill-dots li .skill-progress i {
  margin-right: 10px;
  vertical-align: inherit;
  color: #eeeeee;
}
ul.skill-dots li .skill-progress i.active {
  color: #ff4d57;
}
ul.skill-dots li .skill-progress i.active:nth-child(1) {
  -webkit-animation: skills 1s;
  animation: skills 1s;
}
ul.skill-dots li .skill-progress i.active:nth-child(2) {
  -webkit-animation: skills 2s;
  animation: skills 2s;
}
ul.skill-dots li .skill-progress i.active:nth-child(3) {
  -webkit-animation: skills 3s;
  animation: skills 3s;
}
ul.skill-dots li .skill-progress i.active:nth-child(4) {
  -webkit-animation: skills 4s;
  animation: skills 4s;
}
ul.skill-dots li .skill-progress i.active:nth-child(5) {
  -webkit-animation: skills 5s;
  animation: skills 5s;
}
ul.skill-dots li .skill-progress i.active:nth-child(6) {
  -webkit-animation: skills 6s;
  animation: skills 6s;
}
ul.skill-dots li .skill-progress i.active:nth-child(7) {
  -webkit-animation: skills 7s;
  animation: skills 7s;
}
ul.skill-dots li .skill-progress i.active:nth-child(8) {
  -webkit-animation: skills 8s;
  animation: skills 8s;
}
ul.skill-dots li .skill-progress i.active:nth-child(9) {
  -webkit-animation: skills 9s;
  animation: skills 9s;
}
ul.skill-dots li .skill-progress i.active:nth-child(10) {
  -webkit-animation: skills 10s;
  animation: skills 10s;
}
ul.skill-dots li .skill-progress i:before {
  content: "\f111";
}
body {
  font-family: "Poppins", sans-serif;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  color: #252525;
  font-family: "Poppins", sans-serif;
  font-weight: 300;
  font-variant-ligatures: common-ligatures;
  margin-top: 0;
  margin-bottom: 0;
}
h1 {
  font-size: 18px;
  line-height: 1em;
  font-weight: 700;
  margin-bottom: 15px;
  letter-spacing: 0.75px;
}
h2 {
  font-size: 19px;
  line-height: 19px;
  font-weight: 400;
  margin-bottom: 13px;
  letter-spacing: 1.2px;
}
h3 {
  font-size: 31px;
  line-height: 31px;
  font-weight: 400;
  margin-bottom: 25px;
}
h4 {
  font-size: 20px;
  line-height: 20px;
  margin-bottom: 10px;
}
h5 {
  font-size: 18px;
  line-height: 1.8em;
  font-weight: 600;
}
p {
  font-family: "Poppins", sans-serif;
  font-size: 14px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0.75px;
  color: #424250;
}
p.content {
  margin: 15px 0 20px;
}
hr.title {
  width: 65px;
  margin: 0 0 0;
  border-width: 4px;
  border-color: #ff4d57;
}
.circle {
  padding: 20px 20px;
  border-radius: 50%;
  background-color: #ff4d57;
  color: #fff;
  width: 100px;
  height: 90px;
  z-index: 2;
  line-height: 1.1;
}
.how-it-works.row .col-2.full-left::after {
  height: 100%;
  left: 50%;
}

.how-it-works.row .col-2 {
  align-self: stretch;
}
.how-it-works.row .col-2::after {
  content: "";
  position: absolute;
  border-left: 3px solid #ff4d57;
  z-index: 1;
}
.how-it-works.row .col-2.bottom::after {
  height: 50%;
  left: 50%;
  top: 50%;
}
.how-it-works.row .col-2.full::after {
  height: 100%;
  left: calc(50% - 3px);
}
.how-it-works.row .col-2.top::after {
  height: 50%;
  left: 50%;
  top: 0;
}

.timeline div {
  padding: 0;
  height: 40px;
}
.timeline hr {
  border-top: 3px solid #ff4d57;
  margin: 0px;
  top: 17px;
  position: relative;
  height: 5px;
}
.timeline .col-2 {
  display: flex;
  overflow: hidden;
}
.timeline .corner {
  border: 3px solid #ff4d57;
  width: 100%;
  position: relative;
  border-radius: 15px;
}
.timeline .top-right {
  left: 50%;
  top: -50%;
}
.timeline .left-bottom {
  left: -50%;
  top: calc(50% - 3.2px);
}
.timeline .top-left {
  left: -50%;
  top: -50%;
}
.timeline .right-bottom {
  left: 50%;
  top: calc(50% - 3.2px);
}
.skill-bar-1 {
  width: 1% !important;
  -moz-animation: "skill-animation-1" 2s ease-out;
  -webkit-animation: "skill-animation-1" 2s ease-out;
}
.skill-bar-2 {
  width: 2% !important;
  -moz-animation: "skill-animation-2" 2s ease-out;
  -webkit-animation: "skill-animation-2" 2s ease-out;
}
.skill-bar-3 {
  width: 3% !important;
  -moz-animation: "skill-animation-3" 2s ease-out;
  -webkit-animation: "skill-animation-3" 2s ease-out;
}
.skill-bar-4 {
  width: 4% !important;
  -moz-animation: "skill-animation-4" 2s ease-out;
  -webkit-animation: "skill-animation-4" 2s ease-out;
}
.skill-bar-5 {
  width: 5% !important;
  -moz-animation: "skill-animation-5" 2s ease-out;
  -webkit-animation: "skill-animation-5" 2s ease-out;
}
.skill-bar-6 {
  width: 6% !important;
  -moz-animation: "skill-animation-6" 2s ease-out;
  -webkit-animation: "skill-animation-6" 2s ease-out;
}
.skill-bar-7 {
  width: 7% !important;
  -moz-animation: "skill-animation-7" 2s ease-out;
  -webkit-animation: "skill-animation-7" 2s ease-out;
}
.skill-bar-8 {
  width: 8% !important;
  -moz-animation: "skill-animation-8" 2s ease-out;
  -webkit-animation: "skill-animation-8" 2s ease-out;
}
.skill-bar-9 {
  width: 9% !important;
  -moz-animation: "skill-animation-9" 2s ease-out;
  -webkit-animation: "skill-animation-9" 2s ease-out;
}
.skill-bar-10 {
  width: 10% !important;
  -moz-animation: "skill-animation-10" 2s ease-out;
  -webkit-animation: "skill-animation-10" 2s ease-out;
}
.skill-bar-11 {
  width: 11% !important;
  -moz-animation: "skill-animation-11" 2s ease-out;
  -webkit-animation: "skill-animation-11" 2s ease-out;
}
.skill-bar-12 {
  width: 12% !important;
  -moz-animation: "skill-animation-12" 2s ease-out;
  -webkit-animation: "skill-animation-12" 2s ease-out;
}
.skill-bar-13 {
  width: 13% !important;
  -moz-animation: "skill-animation-13" 2s ease-out;
  -webkit-animation: "skill-animation-13" 2s ease-out;
}
.skill-bar-14 {
  width: 14% !important;
  -moz-animation: "skill-animation-14" 2s ease-out;
  -webkit-animation: "skill-animation-14" 2s ease-out;
}
.skill-bar-15 {
  width: 15% !important;
  -moz-animation: "skill-animation-15" 2s ease-out;
  -webkit-animation: "skill-animation-15" 2s ease-out;
}
.skill-bar-16 {
  width: 16% !important;
  -moz-animation: "skill-animation-16" 2s ease-out;
  -webkit-animation: "skill-animation-16" 2s ease-out;
}
.skill-bar-17 {
  width: 17% !important;
  -moz-animation: "skill-animation-17" 2s ease-out;
  -webkit-animation: "skill-animation-17" 2s ease-out;
}
.skill-bar-18 {
  width: 18% !important;
  -moz-animation: "skill-animation-18" 2s ease-out;
  -webkit-animation: "skill-animation-18" 2s ease-out;
}
.skill-bar-19 {
  width: 19% !important;
  -moz-animation: "skill-animation-19" 2s ease-out;
  -webkit-animation: "skill-animation-19" 2s ease-out;
}
.skill-bar-20 {
  width: 20% !important;
  -moz-animation: "skill-animation-20" 2s ease-out;
  -webkit-animation: "skill-animation-20" 2s ease-out;
}
.skill-bar-21 {
  width: 21% !important;
  -moz-animation: "skill-animation-21" 2s ease-out;
  -webkit-animation: "skill-animation-21" 2s ease-out;
}
.skill-bar-22 {
  width: 22% !important;
  -moz-animation: "skill-animation-22" 2s ease-out;
  -webkit-animation: "skill-animation-22" 2s ease-out;
}
.skill-bar-23 {
  width: 23% !important;
  -moz-animation: "skill-animation-23" 2s ease-out;
  -webkit-animation: "skill-animation-23" 2s ease-out;
}
.skill-bar-24 {
  width: 24% !important;
  -moz-animation: "skill-animation-24" 2s ease-out;
  -webkit-animation: "skill-animation-24" 2s ease-out;
}
.skill-bar-25 {
  width: 25% !important;
  -moz-animation: "skill-animation-25" 2s ease-out;
  -webkit-animation: "skill-animation-25" 2s ease-out;
}
.skill-bar-26 {
  width: 26% !important;
  -moz-animation: "skill-animation-26" 2s ease-out;
  -webkit-animation: "skill-animation-26" 2s ease-out;
}
.skill-bar-27 {
  width: 27% !important;
  -moz-animation: "skill-animation-27" 2s ease-out;
  -webkit-animation: "skill-animation-27" 2s ease-out;
}
.skill-bar-28 {
  width: 28% !important;
  -moz-animation: "skill-animation-28" 2s ease-out;
  -webkit-animation: "skill-animation-28" 2s ease-out;
}
.skill-bar-29 {
  width: 29% !important;
  -moz-animation: "skill-animation-29" 2s ease-out;
  -webkit-animation: "skill-animation-29" 2s ease-out;
}
.skill-bar-30 {
  width: 30% !important;
  -moz-animation: "skill-animation-30" 2s ease-out;
  -webkit-animation: "skill-animation-30" 2s ease-out;
}
.skill-bar-31 {
  width: 31% !important;
  -moz-animation: "skill-animation-31" 2s ease-out;
  -webkit-animation: "skill-animation-31" 2s ease-out;
}
.skill-bar-32 {
  width: 32% !important;
  -moz-animation: "skill-animation-32" 2s ease-out;
  -webkit-animation: "skill-animation-32" 2s ease-out;
}
.skill-bar-33 {
  width: 33% !important;
  -moz-animation: "skill-animation-33" 2s ease-out;
  -webkit-animation: "skill-animation-33" 2s ease-out;
}
.skill-bar-34 {
  width: 34% !important;
  -moz-animation: "skill-animation-34" 2s ease-out;
  -webkit-animation: "skill-animation-34" 2s ease-out;
}
.skill-bar-35 {
  width: 35% !important;
  -moz-animation: "skill-animation-35" 2s ease-out;
  -webkit-animation: "skill-animation-35" 2s ease-out;
}
.skill-bar-36 {
  width: 36% !important;
  -moz-animation: "skill-animation-36" 2s ease-out;
  -webkit-animation: "skill-animation-36" 2s ease-out;
}
.skill-bar-37 {
  width: 37% !important;
  -moz-animation: "skill-animation-37" 2s ease-out;
  -webkit-animation: "skill-animation-37" 2s ease-out;
}
.skill-bar-38 {
  width: 38% !important;
  -moz-animation: "skill-animation-38" 2s ease-out;
  -webkit-animation: "skill-animation-38" 2s ease-out;
}
.skill-bar-39 {
  width: 39% !important;
  -moz-animation: "skill-animation-39" 2s ease-out;
  -webkit-animation: "skill-animation-39" 2s ease-out;
}
.skill-bar-40 {
  width: 40% !important;
  -moz-animation: "skill-animation-40" 2s ease-out;
  -webkit-animation: "skill-animation-40" 2s ease-out;
}
.skill-bar-41 {
  width: 41% !important;
  -moz-animation: "skill-animation-41" 2s ease-out;
  -webkit-animation: "skill-animation-41" 2s ease-out;
}
.skill-bar-42 {
  width: 42% !important;
  -moz-animation: "skill-animation-42" 2s ease-out;
  -webkit-animation: "skill-animation-42" 2s ease-out;
}
.skill-bar-43 {
  width: 43% !important;
  -moz-animation: "skill-animation-43" 2s ease-out;
  -webkit-animation: "skill-animation-43" 2s ease-out;
}
.skill-bar-44 {
  width: 44% !important;
  -moz-animation: "skill-animation-44" 2s ease-out;
  -webkit-animation: "skill-animation-44" 2s ease-out;
}
.skill-bar-45 {
  width: 45% !important;
  -moz-animation: "skill-animation-45" 2s ease-out;
  -webkit-animation: "skill-animation-45" 2s ease-out;
}
.skill-bar-46 {
  width: 46% !important;
  -moz-animation: "skill-animation-46" 2s ease-out;
  -webkit-animation: "skill-animation-46" 2s ease-out;
}
.skill-bar-47 {
  width: 47% !important;
  -moz-animation: "skill-animation-47" 2s ease-out;
  -webkit-animation: "skill-animation-47" 2s ease-out;
}
.skill-bar-48 {
  width: 48% !important;
  -moz-animation: "skill-animation-48" 2s ease-out;
  -webkit-animation: "skill-animation-48" 2s ease-out;
}
.skill-bar-49 {
  width: 49% !important;
  -moz-animation: "skill-animation-49" 2s ease-out;
  -webkit-animation: "skill-animation-49" 2s ease-out;
}
.skill-bar-50 {
  width: 50% !important;
  -moz-animation: "skill-animation-50" 2s ease-out;
  -webkit-animation: "skill-animation-50" 2s ease-out;
}
.skill-bar-51 {
  width: 51% !important;
  -moz-animation: "skill-animation-51" 2s ease-out;
  -webkit-animation: "skill-animation-51" 2s ease-out;
}
.skill-bar-52 {
  width: 52% !important;
  -moz-animation: "skill-animation-52" 2s ease-out;
  -webkit-animation: "skill-animation-52" 2s ease-out;
}
.skill-bar-53 {
  width: 53% !important;
  -moz-animation: "skill-animation-53" 2s ease-out;
  -webkit-animation: "skill-animation-53" 2s ease-out;
}
.skill-bar-54 {
  width: 54% !important;
  -moz-animation: "skill-animation-54" 2s ease-out;
  -webkit-animation: "skill-animation-54" 2s ease-out;
}
.skill-bar-55 {
  width: 55% !important;
  -moz-animation: "skill-animation-55" 2s ease-out;
  -webkit-animation: "skill-animation-55" 2s ease-out;
}
.skill-bar-56 {
  width: 56% !important;
  -moz-animation: "skill-animation-56" 2s ease-out;
  -webkit-animation: "skill-animation-56" 2s ease-out;
}
.skill-bar-57 {
  width: 57% !important;
  -moz-animation: "skill-animation-57" 2s ease-out;
  -webkit-animation: "skill-animation-57" 2s ease-out;
}
.skill-bar-58 {
  width: 58% !important;
  -moz-animation: "skill-animation-58" 2s ease-out;
  -webkit-animation: "skill-animation-58" 2s ease-out;
}
.skill-bar-59 {
  width: 59% !important;
  -moz-animation: "skill-animation-59" 2s ease-out;
  -webkit-animation: "skill-animation-59" 2s ease-out;
}
.skill-bar-60 {
  width: 60% !important;
  -moz-animation: "skill-animation-60" 2s ease-out;
  -webkit-animation: "skill-animation-60" 2s ease-out;
}
.skill-bar-61 {
  width: 61% !important;
  -moz-animation: "skill-animation-61" 2s ease-out;
  -webkit-animation: "skill-animation-61" 2s ease-out;
}
.skill-bar-62 {
  width: 62% !important;
  -moz-animation: "skill-animation-62" 2s ease-out;
  -webkit-animation: "skill-animation-62" 2s ease-out;
}
.skill-bar-63 {
  width: 63% !important;
  -moz-animation: "skill-animation-63" 2s ease-out;
  -webkit-animation: "skill-animation-63" 2s ease-out;
}
.skill-bar-64 {
  width: 64% !important;
  -moz-animation: "skill-animation-64" 2s ease-out;
  -webkit-animation: "skill-animation-64" 2s ease-out;
}
.skill-bar-65 {
  width: 65% !important;
  -moz-animation: "skill-animation-65" 2s ease-out;
  -webkit-animation: "skill-animation-65" 2s ease-out;
}
.skill-bar-66 {
  width: 66% !important;
  -moz-animation: "skill-animation-66" 2s ease-out;
  -webkit-animation: "skill-animation-66" 2s ease-out;
}
.skill-bar-67 {
  width: 67% !important;
  -moz-animation: "skill-animation-67" 2s ease-out;
  -webkit-animation: "skill-animation-67" 2s ease-out;
}
.skill-bar-68 {
  width: 68% !important;
  -moz-animation: "skill-animation-68" 2s ease-out;
  -webkit-animation: "skill-animation-68" 2s ease-out;
}
.skill-bar-69 {
  width: 69% !important;
  -moz-animation: "skill-animation-69" 2s ease-out;
  -webkit-animation: "skill-animation-69" 2s ease-out;
}
.skill-bar-70 {
  width: 70% !important;
  -moz-animation: "skill-animation-70" 2s ease-out;
  -webkit-animation: "skill-animation-70" 2s ease-out;
}
.skill-bar-71 {
  width: 71% !important;
  -moz-animation: "skill-animation-71" 2s ease-out;
  -webkit-animation: "skill-animation-71" 2s ease-out;
}
.skill-bar-72 {
  width: 72% !important;
  -moz-animation: "skill-animation-72" 2s ease-out;
  -webkit-animation: "skill-animation-72" 2s ease-out;
}
.skill-bar-73 {
  width: 73% !important;
  -moz-animation: "skill-animation-73" 2s ease-out;
  -webkit-animation: "skill-animation-73" 2s ease-out;
}
.skill-bar-74 {
  width: 74% !important;
  -moz-animation: "skill-animation-74" 2s ease-out;
  -webkit-animation: "skill-animation-74" 2s ease-out;
}
.skill-bar-75 {
  width: 75% !important;
  -moz-animation: "skill-animation-75" 2s ease-out;
  -webkit-animation: "skill-animation-75" 2s ease-out;
}
.skill-bar-76 {
  width: 76% !important;
  -moz-animation: "skill-animation-76" 2s ease-out;
  -webkit-animation: "skill-animation-76" 2s ease-out;
}
.skill-bar-77 {
  width: 77% !important;
  -moz-animation: "skill-animation-77" 2s ease-out;
  -webkit-animation: "skill-animation-77" 2s ease-out;
}
.skill-bar-78 {
  width: 78% !important;
  -moz-animation: "skill-animation-78" 2s ease-out;
  -webkit-animation: "skill-animation-78" 2s ease-out;
}
.skill-bar-79 {
  width: 79% !important;
  -moz-animation: "skill-animation-79" 2s ease-out;
  -webkit-animation: "skill-animation-79" 2s ease-out;
}
.skill-bar-80 {
  width: 80% !important;
  -moz-animation: "skill-animation-80" 2s ease-out;
  -webkit-animation: "skill-animation-80" 2s ease-out;
}
.skill-bar-81 {
  width: 81% !important;
  -moz-animation: "skill-animation-81" 2s ease-out;
  -webkit-animation: "skill-animation-81" 2s ease-out;
}
.skill-bar-82 {
  width: 82% !important;
  -moz-animation: "skill-animation-82" 2s ease-out;
  -webkit-animation: "skill-animation-82" 2s ease-out;
}
.skill-bar-83 {
  width: 83% !important;
  -moz-animation: "skill-animation-83" 2s ease-out;
  -webkit-animation: "skill-animation-83" 2s ease-out;
}
.skill-bar-84 {
  width: 84% !important;
  -moz-animation: "skill-animation-84" 2s ease-out;
  -webkit-animation: "skill-animation-84" 2s ease-out;
}
.skill-bar-85 {
  width: 85% !important;
  -moz-animation: "skill-animation-85" 2s ease-out;
  -webkit-animation: "skill-animation-85" 2s ease-out;
}
.skill-bar-86 {
  width: 86% !important;
  -moz-animation: "skill-animation-86" 2s ease-out;
  -webkit-animation: "skill-animation-86" 2s ease-out;
}
.skill-bar-87 {
  width: 87% !important;
  -moz-animation: "skill-animation-87" 2s ease-out;
  -webkit-animation: "skill-animation-87" 2s ease-out;
}
.skill-bar-88 {
  width: 88% !important;
  -moz-animation: "skill-animation-88" 2s ease-out;
  -webkit-animation: "skill-animation-88" 2s ease-out;
}
.skill-bar-89 {
  width: 89% !important;
  -moz-animation: "skill-animation-89" 2s ease-out;
  -webkit-animation: "skill-animation-89" 2s ease-out;
}
.skill-bar-90 {
  width: 90% !important;
  -moz-animation: "skill-animation-90" 2s ease-out;
  -webkit-animation: "skill-animation-90" 2s ease-out;
}
.skill-bar-91 {
  width: 91% !important;
  -moz-animation: "skill-animation-91" 2s ease-out;
  -webkit-animation: "skill-animation-91" 2s ease-out;
}
.skill-bar-92 {
  width: 92% !important;
  -moz-animation: "skill-animation-92" 2s ease-out;
  -webkit-animation: "skill-animation-92" 2s ease-out;
}
.skill-bar-93 {
  width: 93% !important;
  -moz-animation: "skill-animation-93" 2s ease-out;
  -webkit-animation: "skill-animation-93" 2s ease-out;
}
.skill-bar-94 {
  width: 94% !important;
  -moz-animation: "skill-animation-94" 2s ease-out;
  -webkit-animation: "skill-animation-94" 2s ease-out;
}
.skill-bar-95 {
  width: 95% !important;
  -moz-animation: "skill-animation-95" 2s ease-out;
  -webkit-animation: "skill-animation-95" 2s ease-out;
}
.skill-bar-96 {
  width: 96% !important;
  -moz-animation: "skill-animation-96" 2s ease-out;
  -webkit-animation: "skill-animation-96" 2s ease-out;
}
.skill-bar-97 {
  width: 97% !important;
  -moz-animation: "skill-animation-97" 2s ease-out;
  -webkit-animation: "skill-animation-97" 2s ease-out;
}
.skill-bar-98 {
  width: 98% !important;
  -moz-animation: "skill-animation-98" 2s ease-out;
  -webkit-animation: "skill-animation-98" 2s ease-out;
}
.skill-bar-99 {
  width: 99% !important;
  -moz-animation: "skill-animation-99" 2s ease-out;
  -webkit-animation: "skill-animation-99" 2s ease-out;
}
.skill-bar-100 {
  width: 100% !important;
  -moz-animation: "skill-animation-100" 2s ease-out;
  -webkit-animation: "skill-animation-100" 2s ease-out;
}
</style>