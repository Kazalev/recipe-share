<template>
  <div>
    <!-- <div class="d-flex justify-content-center">
      <ul class="pagination">
        <li class="page-item disabled">
          <a class="page-link" href="#">&laquo;</a>
        </li>
        <li class="page-item active">
          <a class="page-link" href="#">1</a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">2</a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">3</a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">4</a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">5</a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">&raquo;</a>
        </li>
      </ul>
    </div>-->
    <main role="main">
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/food4.jpg" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/food2.jpg" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/food1.jpg" class="d-block w-100" alt="..." />
          </div>
        </div>
        <a
          class="carousel-control-prev"
          href="#carouselExampleIndicators"
          role="button"
          data-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleIndicators"
          role="button"
          data-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>

      <div class="container marketing p-5">
        <!-- Three columns of text below the carousel -->
        
        <div class="row">
          <div class="col-lg-4">
            <img
              class="rounded-circle"
              src="../assets/salads2.jpg"
              alt="Generic placeholder image"
              width="140"
              height="140"
            />
            <h2>Салати</h2>
            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod. Nullam id dolor id nibh ultricies vehicula ut id elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.</p>
            <p>
              <a class="btn btn-secondary" href="#" role="button">View details &raquo;</a>
            </p>
          </div>
          <!-- /.col-lg-4 -->
          <div class="col-lg-4">
            <img
              class="rounded-circle"
              src="../assets/main.jpg"
              alt="Generic placeholder image"
              width="140"
              height="140"
            />
            <h2>Основно</h2>
            <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
            <p>
              <a class="btn btn-secondary" href="#" role="button">View details &raquo;</a>
            </p>
          </div>
          <!-- /.col-lg-4 -->
          <div class="col-lg-4">
            <img
              class="rounded-circle"
              src="../assets/dessert1.jpg"
              alt="Generic placeholder image"
              width="140"
              height="140"
            />
            <h2>Десерти</h2>
            <p>Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
            <p>
              <a class="btn btn-secondary" href="#" role="button">View details &raquo;</a>
            </p>
          </div>
          <!-- /.col-lg-4 -->
        </div>

        <!-- START THE FEATURETTES -->

        <hr class="featurette-divider" />

        <div class="row featurette">
          <div class="col-md-7">
            <blockquote class="blockquote text-left pt-5">
              <!-- <h2 class="featurette-heading">
              Oh yeah, it's that good.
              <span class="text-muted">See for yourself.</span>
              </h2>-->
              <p
                class="lead"
              >„Едно от най-чудесните неща в живота е, че периодично трябва да прекратяваме дейността, с която сме се захванали, за да посветим своето внимание на храненето.“</p>
              <footer class="blockquote-footer">
                <cite title="Source Title">Лучано Павароти</cite>
              </footer>
            </blockquote>
            </div>
          <div class="col-md-5">
            <img
              class="featurette-image img-fluid mx-auto"
              src="../assets/img04.jpg"
              alt="Generic placeholder image"
            />
          </div>
        </div>

        <hr class="featurette-divider" />

        <div class="row featurette">
          <div class="col-md-7 order-md-2">
            <blockquote class="blockquote text-right pt-5">
              <!-- <h2 class="featurette-heading">
              Oh yeah, it's that good.
              <span class="text-muted">See for yourself.</span>
              </h2>-->
              <p
                class="lead"
              >„Водата е много важна част от нашата диета. Пийте много вода и избягвайте празните калории от продукти като безалкохолни напитки, енергийни напитки или сокове с добавена захар.“</p>
              <footer class="blockquote-footer">
                <cite title="Source Title">Джейми Оливър</cite>
              </footer>
            </blockquote>
          </div>
          <div class="col-md-5 order-md-1">
            <img
              class="featurette-image img-fluid mx-auto"
              src="../assets/water.jpg"
              alt="Generic placeholder image"
            />
          </div>
        </div>

        <hr class="featurette-divider" />

        <div class="row featurette">
          <div class="col-md-7">
            <h2 class="featurette-heading">
              And lastly, this one.
              <span class="text-muted">Checkmate.</span>
            </h2>
            <p
              class="lead"
            >Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
          </div>
          <div class="col-md-5">
            <img
              class="featurette-image img-fluid mx-auto"
              src="../assets/food3.jpg"
              alt="Generic placeholder image"
            />
          </div>
        </div>

        <!-- /END THE FEATURETTES -->
      </div>
      <!-- /.container -->
    </main>
  </div>
</template>

<script>
import { db } from "../firebase";

export default {
  name: "Home",
  data: function() {
    return {
      recipes: []
    };
  },
  firestore: {
    recipes: db.collection("Recipes").orderBy("name")
  }
};
</script>

<style scoped>
.container {
  background: #3b4a4a;
  opacity: 0.9;
}

.carousel-inner {
  height: 450px;
}

.col-lg-4 {
  border-radius: 4px;
  padding: 4px;
  opacity: 0.9;
}
</style>
