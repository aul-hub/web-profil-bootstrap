<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1"
    />
    <title>Bootstrap demo</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />

    <!-- My CSS -->
    <link
      rel="stylesheet"
      href="style.css"
    />
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg bg-danger shadow-sm">
      <div class="container">
        <a
          class="navbar-brand"
          href="#"
          >Evi Aulia</a
        >
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse"
          id="navbarNav"
        >
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a
                class="nav-link active"
                aria-current="page"
                href="#"
                >Home</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
                >About</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
                >Galeri</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
                >Contact</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Akhir Navbar -->

    <!-- Awal Jumbotron -->
    <section class="jumbotron text-center">
      <img
        src="auliaaa.jpg"
        alt="Aul"
        width="200"
        class="rounded-circle img-thumbnail"
      />
      <h1 class="display-4">Evi Aulia</h1>
      <p class="lead">Wanita Karir</p>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1440 320"
      >
        <path
          fill="#a2d9ff"
          fill-opacity="1"
          d="M0,64L17.1,74.7C34.3,85,69,107,103,138.7C137.1,171,171,213,206,240C240,267,274,277,309,245.3C342.9,213,377,139,411,117.3C445.7,96,480,128,514,128C548.6,128,583,96,617,90.7C651.4,85,686,107,720,128C754.3,149,789,171,823,170.7C857.1,171,891,149,926,133.3C960,117,994,107,1029,106.7C1062.9,107,1097,117,1131,144C1165.7,171,1200,213,1234,213.3C1268.6,213,1303,171,1337,144C1371.4,117,1406,107,1423,101.3L1440,96L1440,320L1422.9,320C1405.7,320,1371,320,1337,320C1302.9,320,1269,320,1234,320C1200,320,1166,320,1131,320C1097.1,320,1063,320,1029,320C994.3,320,960,320,926,320C891.4,320,857,320,823,320C788.6,320,754,320,720,320C685.7,320,651,320,617,320C582.9,320,549,320,514,320C480,320,446,320,411,320C377.1,320,343,320,309,320C274.3,320,240,320,206,320C171.4,320,137,320,103,320C68.6,320,34,320,17,320L0,320Z"
        ></path>
      </svg>
    </section>

    <!-- Akhir Jumbotron -->

    <!-- About -->
    <section id="about">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>About Me</h2>
          </div>
        </div>
        <div class="row justify-content-center fs-5 text-center">
          <div class="col-md-4">
            <p>Saya seorang mahasiswa yang ingin menjadi wanita karir dan berkelas. Menjadi wanita intrepeneur dan mempunya soft skill itu impian saya.</p>
          </div>
          <div class="col-md-4">
            <p>Saya slalu suka melakukan kegiatan yang menarik dan mendapatkan sertifikat sekaligus benefit dan bisa berkolaborasi dengan orang-orang hebat.</p>
          </div>
        </div>
      </div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1440 320"
      >
        <path
          fill="#ffe4c4"
          fill-opacity="1"
          d="M0,64L20,74.7C40,85,80,107,120,106.7C160,107,200,85,240,112C280,139,320,213,360,224C400,235,440,181,480,160C520,139,560,149,600,154.7C640,160,680,160,720,144C760,128,800,96,840,112C880,128,920,192,960,213.3C1000,235,1040,213,1080,197.3C1120,181,1160,171,1200,176C1240,181,1280,203,1320,192C1360,181,1400,139,1420,117.3L1440,96L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- Akhir About -->

    <!-- Awal Galeri -->
    <section id="galeri">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <p>My Picture</p>
          </div>
        </div>
        <div class="row justify-content-center fs-5 text-center">
          <div class="col-md-4 mb-3">
            <div class="card">
              <img
                src="auliaaa.jpg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <p class="card-text">wislisht smart woman</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img
                src="auliaaa.jpg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <p class="card-text">funny woman</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img
                src="auliaaa.jpg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <p class="card-text">Strong woman</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1440 320"
      >
        <path
          fill="#ffe4c4"
          fill-opacity="1"
          d="M0,96L40,128C80,160,160,224,240,250.7C320,277,400,267,480,234.7C560,203,640,149,720,122.7C800,96,880,96,960,128C1040,160,1120,224,1200,213.3C1280,203,1360,117,1400,74.7L1440,32L1440,0L1400,0C1360,0,1280,0,1200,0C1120,0,1040,0,960,0C880,0,800,0,720,0C640,0,560,0,480,0C400,0,320,0,240,0C160,0,80,0,40,0L0,0Z"
        ></path>
      </svg>
    </section>
    <!-- Akhir Galeri -->

    <!-- Awal Contact -->
    <section id="contact">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Contact Me</h2>
          </div>
        </div>
        <div class="row justify-content-center">
            <div class="col-8-md">
                <form>
                    <div class="mb-3">
                      <label for="name" class="form-label">Nama Lengkap</label>
                      <input type="text" class="form-control" id="name" aria-describedby="name">
                    </div>
                    <div class="mb-3">
                      <label for="email" class="form-label">Email</label>
                      <input type="email" class="form-control" id="email" aria-describedby="email">
                    </div>
                    <div class="mb-3">
                        <label for="pesan" class="form-label">Email address</label>
                        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
                      </div>
                      <div class="mb-3">
                        <label for="pesan" class="form-label">pesan</label>
                        <textarea class="form-control" id="pesan" rows="3"></textarea>
                      </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                  </form>
            </div>
      </div>
    </section>
    <!-- Akhir Contact -->

    <!-- footer -->
     <footer class="bg-danger">
        <p>Created with love by <a href="https://l.instagram.com/?u=https%3A%2F%2Fwww.instagram.com%2Faulviawh05%3Ffbclid%3DPAZXh0bgNhZW0CMTEAAaYi095OfPIGurUe_f2gyOtpNYUy9wA0SrJCXHW5if7wRRJf-u1JYvX1BhU_aem_qlBVshZAachqMvewTlTtfA&e=AT09CTqA9U6IAeJo0ZUuFequY_n8mQVNWoJGq7wP1uRUiFO3D7d-TJsZe2bhqaGx6aR1Cx_66XoLQH77XZqJgiek5xltHDyriKkj3UU">Aull</a>
        </p>
     </footer>

    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
