<script lang="ts">
	import bookCover from '$assets/book_cover.png';
	import phoneCover from '$assets/phone_cover.png';
  import {Button} from '$components';
</script>

<section class="hero">
	<div class="hero-showcase text-center bold">
		<h1 class="purple">MOVE TO</h1>
		<h1 class="purple mb-xs">SPAIN</h1>
		<h4 class="italic semi-bold">There's no need to make the same mistakes I made.</h4>
		<img class="book-cover" src={bookCover} alt="book cover" />
		<img class="phone-cover" src={phoneCover} alt="phone cover" />
	</div>
	<div class="hero-text white text-center">
    <h1>THIS EBOOK WILL</h1>
    <h1>SAVE TOU MONEY,</h1>
    <h1 class="mb-m">TIME & NERVES.</h1>
    <p class="light-grey mb-l">
      I moved to Spain seven years ago. The process was painful and difficult. I learned most things the hard way: finding a job, getting a visa, calculating my cost of living, choosing an apartment. That's why I wrote this e-bbok, to tell you how I did it. No bullshit, no stress.
    </p>
    <Button>purchase E-BOOK FOR 10$</Button>
  </div>
</section>

<style>
  .hero {
    display: flex;
    overflow-y: hidden;
  }

  .hero-showcase {
    position: relative;
    width: 50%;
    padding: 100px 16px 0 16px;
    background: linear-gradient(135deg, #e2cbff, #e2cbff 25%, #deeaff 50%, #ece5ff 75%, #927bce);
  }

  .hero-text {
    padding: 100px 5%;
    width: 50%;
    background-color: #000000;
  }

  .book-cover {
    position: absolute;
    right: 2%;
    transform: translateY(15%);
    width: 65%;
  }

  .phone-cover {
    width: 35%;
    position: absolute;
    right: 52%;
    transform: translateY(40%);
  }
</style>
