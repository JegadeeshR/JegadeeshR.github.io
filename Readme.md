<!-- Teams -->
    <section class="theme section" id="teams">
      <div class="title">
        <h1>My teams</h1>
      </div>

      <div class="teams-center container">
        <div class="glide">
          <div class="glide__track" data-glide-el="track">
            <ul class="glide__slides">
              <li class="glide__slide">
                <div class="team">
                  <div class="img-cover">
                    <img src="./images/profile1.jpg" alt="" />
                  </div>
                  <h3>Someone's name</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Pariatur, excepturi.
                  </p>
                </div>
              </li>
              <li class="glide__slide">
                <div class="team">
                  <div class="img-cover">
                    <img src="./images/profile2.jpg" alt="" />
                  </div>
                  <h3>Someone's name</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Pariatur, excepturi.
                  </p>
                </div>
              </li>
              <li class="glide__slide">
                <div class="team">
                  <div class="img-cover">
                    <img src="./images/profile2.jpg" alt="" />
                  </div>
                  <h3>Someone's name</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Pariatur, excepturi.
                  </p>
                </div>
              </li>
              <li class="glide__slide">
                <div class="team">
                  <div class="img-cover">
                    <img src="./images/profile3.jpg" alt="" />
                  </div>
                  <h3>Someone's name</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Pariatur, excepturi.
                  </p>
                </div>
              </li>
              <li class="glide__slide">
                <div class="team">
                  <div class="img-cover">
                    <img src="./images/profile4.jpg" alt="" />
                  </div>
                  <h3>Someone's name</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Pariatur, excepturi.
                  </p>
                </div>
              </li>
              <li class="glide__slide">
                <div class="team">
                  <div class="img-cover">
                    <img src="./images/profile5.jpg" alt="" />
                  </div>
                  <h3>Someone's name</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Pariatur, excepturi.
                  </p>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    /* Teams */
.team {
  color: #fff;
  background-color: #111;
  padding: 3rem;
  text-align: center;
  border-radius: 1rem;
  border-bottom: 4px solid transparent;
  transition: all 300ms ease-in-out;
}

.team .img-cover {
  overflow: hidden;
  border-radius: 100%;
  border: 4px solid var(--customColor);
  height: 13rem;
  width: 13rem;
  margin: 0 auto;
  transition: all 300ms ease-in-out;
}

.team .img-cover img {
  height: 100%;
  object-fit: cover;
}

.team h3 {
  font-size: 1.6rem;
  margin: 1rem 0;
}

.team p {
  font-size: 1.5rem;
  color: #ccc;
  width: 80%;
  margin: 0 auto 1rem auto;
}

.team:hover {
  border-bottom: 4px solid #fff;
  background-color: var(--customColor);
}

.team:hover .img-cover {
  border-color: #fff;
}