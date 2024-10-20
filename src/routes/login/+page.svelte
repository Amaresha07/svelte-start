<script>
    import {goto} from "$app/navigation";
    let login = () => {
        goto("/home");
    }
</script>


<div class="w-full h-screen border border-black flex justify-center items-center">
    <div class="w-96 h-96 border-2 border-black rounded-lg flex flex-col justify-center items-center p-4">
        <i class="fa-solid fa-right-to-bracket text-4xl mb-5"></i>
        <h1 class="text-2xl font-semibold pb-6">Login</h1>
        <input type="email" name="Email" placeholder="Email" class="border border-black rounded-md w-full h-12 pl-2" required>
        <input type="password" name="Email" placeholder="Password" class="border border-black rounded-md w-full h-12 mt-4 pl-2" required>
        <button class="w-full h-12 bg-black text-white text-xl mt-4 rounded-xl text-center font-semibold hover:bg-white duration-500 hover:text-black hover:border-2 hover:border-black" on:click={login}>Login</button>
    </div>
</div>
