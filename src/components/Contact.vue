<template>
    <div class="bg-neutral-100 py-5">
        <!-- Flex div to hold contact image and contact form-->
        <div class="flex justify-between mb-20 mx-6 sm:mx-16 lg:mx-32 xl:mx-48">
            <!-- Image div -->
            <div>
                <img src="../img/alexander-andrews-JYGnB9gTCls-unsplash.jpg" alt="man with smartphone" class="w-80 rounded-lg mt-10">
            </div>
            <!-- Form div -->
            <div class="">
                <h2 class="text-3xl font-bold mt-10">Connect &#38; Chat</h2>
                <form class="bg-white rounded-lg p-8 my-4 sm:w-80">
                    <label>Email:</label>
                    <input type="email" class="bg-inherit">
                    <label>Message:</label>
                    <input type="text">
                </form>
            </div>
        </div>
    </div>
</template>

<script>

</script>
<style>
form {
    /* width: 420px;
    max-width: 630px;
    margin: 30px auto;
    background: white;
    text-align: left;
    padding: 40px;
    border-radius: 10px; */
}
label {
    color: #aaa;
    display: inline-block;
    margin: 25px 0 15px;
    font-size: 0.6em;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}
input, select {
    display: block;
    padding: 10px 6px;
    width: 100%;
    box-sizing: border-box;
    border: none;
    border-bottom: 1px solid #ddd;
    color: #555;
}
</style>
