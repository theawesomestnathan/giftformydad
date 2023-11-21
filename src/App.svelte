<script lang="ts">
  import Toggle from "./lib/Toggle.svelte";

  import Image1 from "./assets/image1.jpg";
  import Image2 from "./assets/image2.jpg";
  import Image3 from "./assets/image3.jpg";
  import Image4 from "./assets/image4.jpg";
  import Image5 from "./assets/image5.jpg";
  import Image6 from "./assets/image6.jpg";
</script>

<Toggle/>

<div class="pt-56 text-center">
  <h1> Happy Birthday, Dad </h1>

  <p class="pt-5 w-[30rem] mx-auto">
    This website is dedicated to the best dad on the planet,
    who raised me for all of these 11 years. It's his birthday
    today and I decided: "why not use my talent to create 
    something special for my father's birthday?". So, I made
    this website to organize all the things I have for my dad.
    Happy Birthday, dad!
  </p>
</div>

<div class="pt-[40rem] text-center">
  <h1> Poem </h1>

  <p class="pt-5"> 
    There's a person who's been with me all the time,
  </p>
  <p> 
    There’s a person who’s valued in the heart of mine.
  </p>
  <p> 
    He was always there every time I’m sad,
  </p>
  <p> 
    And that person is my dad.
  </p>

  <p class="pt-5"> 
    Even when I have the neediest of needs,
  </p>
  <p> 
    My dad will always do it for me.
  </p>
  <p> 
    Him being here by my side makes me so glad,
  </p>
  <p> 
    Because he’s the best person I could ever have.
  </p>

  <p class="pt-5"> 
    I’m really grateful for all you’ve done for me,
  </p>
  <p> 
    You work the hardest to feed our family.
  </p>
  <p> 
    And now that your a year older, I just wanna say,
  </p>
  <p> 
    I love you dad, and Happy Birthday.
  </p>
</div>

<div class="pt-[40rem] text-center">
  <h1> Memories </h1>

  <div class="flex justify-center">
    <div class="grid grid-cols-3 gap-4 pt-5 w-[50rem]">
      <img src={Image1} alt="memory 1" class="w-full h-auto rounded"/>
      <img src={Image2} alt="memory 2" class="w-full h-auto rounded"/>
      <img src={Image3} alt="memory 3" class="w-96 h-48 rounded"/>
      <img src={Image4} alt="memory 4" class="w-full h-48 rounded"/>
      <img src={Image5} alt="memory 5" class="w-full h-auto rounded"/>
      <img src={Image6} alt="memory 6" class="w-full h-auto rounded"/>
    </div>
  </div>
</div>

<div class="pt-[30rem] text-center pb-[30rem]">
  <h1>
    Message
  </h1>

  <p class="pt-5 w-[30rem] mx-auto"> 
    Dad, I love you very much and I'm happy that your now 38
    years old. I don't have much to give, but I'd thought
    I'd at least use my talent to give you a birthday gift.
  </p>
</div>