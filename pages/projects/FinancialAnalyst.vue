<template>
  <div>
    <section class="wrapper !bg-[#ffffff]">
      <div
        class="container pt-20 xl:pt-28 lg:pt-28 md:pt-28 pb-16 xl:pb-20 lg:pb-20 md:pb-20"
      >
        <div class="flex flex-wrap mx-[-15px] !relative">
          <figure
            class="!rounded-[.4rem] absolute hidden lg:block xl:block px-[15px]"
            style="
              top: 50%;
              right: 0;
              width: 45%;
              height: auto;
              transform: translateY(-50%);
              z-index: 2;
            "
          >
            <img
              class="!rounded-[.4rem]"
              src="https://sandbox-tailwind-template.netlify.app/assets/img/photos/tei1.jpg"
              alt="image"
            /> 
          </figure>
          <div
            class="xl:w-9/12 lg:w-9/12 w-full flex-[0_0_auto] px-[15px] max-w-full !text-center"
          >
            <div class="card !bg-[rgba(246,247,249,1)]">
              <div
                class="card-body xl:!p-10 lg:!p-10 md:!p-10 xxl:!py-24 p-[40px]"
              >
                <div class="flex flex-wrap mx-0">
                  <div
                    class="xl:w-8/12 lg:w-8/12 w-full flex-[0_0_auto] max-w-full xl:!pl-10"
                  >
                    <span
                      class="ratings inline-block relative w-20 h-[0.8rem] leading-none before:text-[rgba(38,43,50,0.1)] after:inline-block after:not-italic after:font-normal after:absolute after:text-[#fcc032] after:content-['\2605\2605\2605\2605\2605'] after:overflow-hidden after:left-0 after:top-0 before:inline-block before:not-italic before:font-normal before:absolute before:text-[#fcc032] before:content-['\2605\2605\2605\2605\2605'] before:overflow-hidden before:left-0 before:top-0 five text-[1rem] !mb-3"
                    ></span>
                    <blockquote
                      class="!pl-0 text-[3rem] mb-0 border-0 !leading-[1.7] font-medium m-[0_0_1rem]"
                    >
                      <p>
                        “Donec id elit non mi porta gravida at eget metus.
                        Vivamus mollis est non commodo luctus, nisi erat
                        porttitor ligula, eget lacinia odio sem nec elit. Duis
                        mollis porta est non commodo luctus.”
                      </p>
                      <div
                        class="flex items-center justify-center !text-center"
                      >
                        <div class="info p-0">
                          <h4 class="tracking-[-0.03em] !mb-1">
                            Coriss Ambady
                          </h4>
                          <p class="!mb-0 text-[.8rem]">Financial Analyst</p>
                        </div>
                      </div>
                    </blockquote>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
