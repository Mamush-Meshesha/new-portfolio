<template>
  <div>
    <div class="bg-[#1d204e]">
      <div
        class="back fixed top-0 right-0 left-0 bottom-0 z-0 backdrop:blur opacity-20"
      ></div>
      <div class="container mx-auto relative h-screen">
        <div class="flex justify-center items-center h-full">
          <div class="leading-[70px]">
            <h1
              class="md:text-7xl text-3xl text-center capitalize font-serif font-bold py-3 text-white"
            >
              Full stack web developer
            </h1>
            <p class="md:text-2xl text-xl text-white text-center">
              Showcasing projects and skills with stunning animations
            </p>
            <div class="flex justify-center py-6">
              <button
                class="bg-[#32a927] h-[50px] flex items-center px-6 text-white rounded-md"
              >
                View Projects
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- about section -->

    <div class="z-10 bg-gray-100 relative">
      <div class="container mx-auto">
        <div
          class="md:grid md:grid-cols-2 flex flex-col-reverse gap-10 w-full h-full items-center"
        >
          <div class="w-[80%] bg-white p-10 rounded-lg">
            <div>
              <h1 class="text-4xl font-bold font-serif">
                Passionate fullstack developer
              </h1>
              <p class="text-2xl py-3 leading-9 text-[#595959]">
                I am a dedicated fullstack developer based in Addis Ababa,
                specializing in creating dynamic web applications. With
                expertise in Nuxt 3 and Tailwind CSS, I craft responsive and
                engaging user experiences that showcase my projects, skills, and
                professional journey. My portfolio reflects my commitment to
                excellence and innovation in every line of code I write.
              </p>
              <button>Get in touch</button>
            </div>
          </div>
          <div class="flex h-full items-center">
            <img
              src="../assets/about.jpeg"
              alt=""
              class="h-[70%] w-[90%] object-cover rounded-md"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- skills -->
    <div class="relative bg-gray-100">
      <div class="container mx-auto">
        <div class="border rounded-md flex p-10 bg-white items-center flex-col">
          <div class="flex justify-center">
            <h1 class="text-4xl">Skills</h1>
          </div>
          <div class="py-10">
            <div class="grid md:grid-cols-4 grid-cols-2 gap-10">
              <div class="flex flex-col items-center">
                <img
                  src="../assets/react.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Reactjs</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/vue.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Vuejs</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/nuxt.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Nuxt</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/tailwind.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Tailwind</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/express.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Express</h1>
              </div>
              <div class="flex flex-col items-center gap-2">
                <img
                  src="../assets/mongo.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>MongoDB</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/node.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Nodejs</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/hasura.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Hasura</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/git.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Git</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/graphql.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Graphql</h1>
              </div>
              <div class="flex flex-col items-center">
                <img
                  src="../assets/ts.png"
                  alt=""
                  class="icon w-20 h-20 rounded-md object-contain"
                />
                <h1>Typescript</h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- projects -->
    <div class="bg-gray-100 h-full relative py-10">
      <div class="mx-auto container">
        <div class="py-10">
          <h1 class="text-4xl">Projects</h1>
        </div>
        <div class="md:grid md:grid-cols-3 md:gap-5">
          <div class="md:w-[30rem] h-auto border rounded-2xl bg-white">
            <div class="">
              <div>
                <img
                  src="~/assets/about.jpeg"
                  alt=""
                  class="w-full h-[300px] object-cover rounded-2xl rounded-b-none"
                />
              </div>
              <div class="p-3">
                <h1>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                  Dolor facere vel molestiae ducimus minima eos perferendis amet
                  ut saepe! Rerum porro animi quia culpa veniam, molestias fuga
                  sunt, unde ipsam est impedit! Iste temporibus sed laborum
                  tempora
                </h1>
              </div>
            </div>
          </div>
          <!-- project 2 -->
          <div class="md:w-[30rem] h-auto border rounded-2xl bg-white">
            <div class="">
              <div>
                <img
                  src="~/assets/about.jpeg"
                  alt=""
                  class="w-full h-[300px] object-cover rounded-2xl rounded-b-none"
                />
              </div>
              <div class="p-3">
                <h1>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                  Dolor facere vel molestiae ducimus minima eos perferendis amet
                  ut saepe! Rerum porro animi quia culpa veniam, molestias fuga
                  sunt, unde ipsam est impedit! Iste temporibus sed laborum
                  tempora
                </h1>
              </div>
            </div>
          </div>
          <!-- project 2 -->
          <div class="md:w-[30rem] h-auto border rounded-2xl bg-white">
            <div class="">
              <div>
                <img
                  src="~/assets/about.jpeg"
                  alt=""
                  class="w-full h-[300px] object-cover rounded-2xl rounded-b-none"
                />
              </div>
              <div class="p-3">
                <h1>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                  Dolor facere vel molestiae ducimus minima eos perferendis amet
                  ut saepe! Rerum porro animi quia culpa veniam, molestias fuga
                  sunt, unde ipsam est impedit! Iste temporibus sed laborum
                  tempora
                </h1>
              </div>
            </div>
          </div>
          <!-- project 2 -->
        </div>
      </div>
    </div>
    <!-- contact -->
    <div class="bg-gray-100 relative py-10">
      <div
        class="container mx-auto border border-gray-300 rounded-lg shadow-lg bg-white p-6"
      >
        <div class="flex justify-center w-full">
          <div>
            <div class="py-4 flex justify-center">
              <h1 class="text-4xl font-bold text-gray-800">Get in Touch</h1>
            </div>
            <div class="w-full py-10">
              <div class="flex flex-col gap-6">
                <div class="relative">
                  <label for="name" class="text-gray-700 py-2">Name</label>
                  <span class="text-red-500 absolute ml-2">*</span>
                  <input
                    type="text"
                    placeholder="Your Name"
                    class="h-12 border border-gray-300 py-2 w-full px-4 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-200"
                  />
                </div>
                <div class="relative">
                  <label for="email" class="text-gray-700">Email</label>
                  <span class="text-red-500 absolute ml-2">*</span>
                  <input
                    type="email"
                    placeholder="Your Email"
                    class="h-12 border border-gray-300 py-2 w-full px-4 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-200"
                  />
                </div>
                <div class="relative">
                  <label for="message" class="text-gray-700">Message</label>
                  <span class="text-red-500 absolute ml-2">*</span>
                </div>
                <textarea
                  placeholder="Write your message here..."
                  class="p-4 min-h-40 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-200"
                ></textarea>
                <button
                  type="submit"
                  class="mt-4 bg-blue-500 text-white font-semibold py-2 rounded-md hover:bg-blue-600 transition duration-200"
                >
                  Send Message
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import image from "../assets/pc.jpg";
</script>

<style scoped>
.back {
  background-image: url("../assets/pc1.png");
  background-size: cover;
  /* Optional: Adjusts the background image size */
  height: 100vh;
}
.icon {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
</style>
