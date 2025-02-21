<template>
  <section class="container mt-5" >
        <div id="judul-benefit" class="text-center">
            <button data-aos="fade-up" class="btn-jud">
                <h4 class="h4-jud poppins-medium">Q & A Silber</h4>
            </button>
        </div>
        <div class="row mt-5 w-auto row-cols-lg-2 row-cols-md-1 row-cols-1">
            <div class="col" data-aos="zoom-in">
                <img src="/img/q_a.png" class="img-fluid" alt="">
            </div>
            <div class="col">
                <div class="accordion" id="accordionExample">
                    <div class="accordion-item rounded-4 border-0 card-tab">
                      <h2 class="accordion-header">
                        <button class="accordion-button poppins-medium" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                          SMK Muhhamadiyah 02 Palembang - SMK Silber ? 
                        </button>
                      </h2>
                      <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
                        <div class="accordion-body ">
                          <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                        </div>
                      </div>
                    </div>
                    <div class="accordion-item rounded-4 card-tab mt-4">
                      <h2 class="accordion-header">
                        <button class="accordion-button collapsed poppins-medium" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                          Berapakah Jurusan di SMK Muhhamadiyah 02 Palembang ? 
                        </button>
                      </h2>
                      <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                        <div class="accordion-body">
                          <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                        </div>
                      </div>
                    </div>
                    <div class="accordion-item rounded-4 card-tab mt-4">
                      <h2 class="accordion-header">
                        <button class="accordion-button collapsed poppins-medium" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                          Mengapa Jurusan TKJ Paling Banyak di Minati ?
                        </button>
                      </h2>
                      <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                        <div class="accordion-body">
                          <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                        </div>
                      </div>
                    </div>
                </div>
            </div>
        </div>
  </section>
</template>

<script>
export default {
  name: "Test",
  created() {},
  data() {
    return {};
  },
  props: {},
  methods: {},
};
</script>

<style lang="scss" scoped></style>