# repository-3-
most important places in india
<!DOCTYPE html>
<html lang="en">
<style>
* {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
}

html,
body {
  height: 100%;
  background-color: #ebe5dd;
}

/* HEADER */

.main {
  margin: auto;
  max-width: 1200px;
}

header {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url(../images/hala.jpg);
  height: 100vh;
  background-size: cover;
  background-position: center;
}

/* NAVIGATION */
.main-list {
  float: right;
  font-variant: small-caps;
  list-style-type: none;
  margin-top: 20px;
  margin-right: 10px;
}

/* Responsive layout */
@media screen and (max-width: 1000px) {
  .main-list {
    font-size: 17px;
  }
}

@media screen and (max-width: 800px) {
  .main-list {
    font-size: 12px;
  }
}

@media screen and (max-width: 650px) {
  .main-list {
    font-size: 7px;
    font-weight: bold;
  }
}

.main-list-item {
  display: inline-block;
}

.main-list-item a {
  text-decoration: none;
  color: white;
  border: 1px solid transparent;
  padding: 5px 20px;
  transition: 0.7s ease;
}

.main-list-item a:hover {
  background-color: rgb(89, 73, 46);
}

.active {
  background-color: rgb(89, 73, 46);
}

.history-list {
  margin-left: 40px;
}

.history-list a {
  text-decoration: none;
}
/* TITLE */
.title {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.heading {
  color: white;
  font-size: 4vw;
  font-variant: small-caps;
}

/* MAIN CONTENT */
.page-wrapper {
  min-height: 100%;
}

/* HISTORY */
.history {
  margin: 20px;
}

.history-para {
  padding: 13px;
}

.history-heading2 {
  margin: 2px;
  padding-top: 20px;
}

/* IMAGE GALLERY */
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  flex: 20%;
  max-width: 20%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}

/* FAMOUS PLACES PAGE */
/* IMAGE GALLERY */
.image-gallery {
  box-sizing: border-box;
  display: flex;
  flex-wrap: wrap;
  margin-left: 10%;
  margin-right: 10%;
}

.gallery {
  border: 1px solid #ccc;
}

.gallery img {
  width: 100%;
  height: auto;
}

.des {
  padding: 15px;
  text-align: center;
}

.responsive {
  margin-top: 10px;
  padding: 0 7px;
  width: 290px;
}

/* Restaurants Page */
.restaurants {
  padding: 10px;
}

.restaurants-link {
  color: #6e0101;
}

/* STOPS Page*/
.stops-link {
  color: blue;
}

/* Hospitals Page */

.hospitals-link {
  color: green;
}

/* FOOTER */
.footer {
  background: #303036;
  color: #d3d3d3;
  height: 400px;
  position: relative;
}

.footer .footer-bottom {
  background-color: #343a40;
  color: #686868;
  text-align: center;
  height: 50px;
  position: absolute;
  bottom: 0px;
  left: 0px;
  width: 100%;
  padding-top: 20px;
}

.footer .footer-content {
  height: 350px;
  display: flex;
}

.footer .footer-content .footer-section {
  flex: 1;
  padding: 25px;
}

.footer .footer-content h1 {
  color: white;
}

.footer-para {
  margin: 10px 0;
}

.footer .footer-content .about .contact span {
  display: block;
  margin-bottom: 8px;
  font-size: 1.1em;
}

.footer .footer-content .about .socials a {
  border: 1px solid gray;
  width: 45px;
  height: 38px;
  padding-top: 5px;
  margin-right: 5px;
  text-align: center;
  display: inline-block;
  font-size: 1.3em;
  text-decoration: none;
  color: #d3d3d3;
  border-radius: 5px;
  transition: all 0.3s;
}

.footer .footer-content .about .socials a:hover {
  color: white;
  border: 1px solid white;
  transition: all 0.3s;
}

.footer-section {
  text-align: center;
}

.logo-text {
  font-variant: initial;
}

.logo-text .logo-span {
  color: #a2c376;
}
</style>

  <body>
    <!-- PAGE WRAPPER -->
    <div class="page-wrapper">
      <div class="history">
        <h1 class="history-heading1">Famous Places </h1>
        <hr />
      </div>
      <!-- IMAGE GALLERY -->
      <div class="image-gallery">
        <!-- IMAGE -->
        <div class="responsive">
          <div class="gallery">
            <a href="https://images.moneycontrol.com/static-mcnews/2022/10/8-delhi-pollution-after-diwali.jpg?impolicy=website&width=770&height=431"
              ><img
                width="200"
                height="200"
                src="https://images.moneycontrol.com/static-mcnews/2022/10/8-delhi-pollution-after-diwali.jpg?impolicy=website&width=770&height=431"
                alt="Kirarki Masjid Matiari"
                title="DELHI"
            /></a>
            <div class="des"><strong>DELHI</strong></div>
          </div>
        </div>
        <!-- // IMAGE -->

        <!-- IMAGE -->
        <div class="responsive">
          <div class="gallery">
            <a
              href="https://images.moneycontrol.com/static-mcnews/2022/12/Mumbai-Bombay-generic-770x435.jpg?impolicy=website&width=770&height=431"
              target="_blank"
              ><img
                width="200"
                height="200"
                src="https://images.moneycontrol.com/static-mcnews/2022/12/Mumbai-Bombay-generic-770x435.jpg?impolicy=website&width=770&height=431"
                alt="MUMBAI"
                title="MUBAI"
            /></a>
            <div class="des">
              <strong>MUMBAI</strong>
            </div>
          </div>
        </div>
        <!-- IMAGE -->
        <div class="responsive">
          <div class="gallery">
            <a href="https://static.india.com/wp-content/uploads/2018/08/Main10-1.jpg"
              ><img
                width="200"
                height="200"
                src="https://static.india.com/wp-content/uploads/2018/08/Main10-1.jpg"
                alt="KOCHI"
                title="KOCHI"
            /></a>
            <div class="des">
              <strong>KOCHI</strong>
            </div>
          </div>
        </div>
        <!-- // IMAGE -->
        <!-- IMAGE -->
        <div class="responsive">
          <div class="gallery">
            <a href="https://cdn.britannica.com/53/176353-050-5B854179/Harmandir-Sahib-Amritsar-Punjab-India.jpg" target="_blank"
              ><img
                width="200"
                height="200"
                src="https://cdn.britannica.com/53/176353-050-5B854179/Harmandir-Sahib-Amritsar-Punjab-India.jpg"
                alt="PUNJAB"
                title="PUNJAB"
            /></a>
            <div class="des"><strong>PUNJAB</strong></div>
          </div>
        </div>
        <!-- // IMAGE -->
        <!-- IMAGE -->
        <div class="responsive">
          <div class="gallery">
            <a href="https://www.adotrip.com/public/images/state/master_images/5f3bb17fddc76-Uttar_Pradesh_Attractions.jpg" target="_blank"
              ><img
                width="200"
                height="200"
                src="https://www.adotrip.com/public/images/state/master_images/5f3bb17fddc76-Uttar_Pradesh_Attractions.jpg"
                alt="UTTAR PRADESH"
                title="UTTAR PRADESH"
            /></a>
            <div class="des">
              <strong>UTTAR PRADESH</strong></div>
          </div>
          </div>
          <!-- // IMAGE -->
        <!-- IMAGE -->
        <div class="responsive">
          <div class="gallery">
            <a href="https://static.toiimg.com/thumb/msid-91006932,width-748,height-499,resizemode=4,imgsize-165776/A-short-guide-to-Nepal-for-budget-travellers.jpg"
              ><img
                width="200"
                height="200"
                src="https://static.toiimg.com/thumb/msid-91006932,width-748,height-499,resizemode=4,imgsize-165776/A-short-guide-to-Nepal-for-budget-travellers.jpg"
                alt="NEPAL"
                title="NEPAL"
            /></a>
            <div class="des">
              <strong>NEPAL</strong></div>
              </div>
              </div>
          
  </body>
</html>
