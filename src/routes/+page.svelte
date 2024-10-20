<script>
    import {goto} from "$app/navigation";
    import { onMount } from "svelte";

    let login = () => {
        goto("/login");
    }

    onMount(() => {
        login();
    });
</script>

<button class="border-2 border-black pl-4 pr-4 pt-2 pb-2 hover:bg-black hover:text-white duration-300">Click</button>

<h1 class="text-4xl font-bold hover:text-green-400 cursor-pointer">Hello</h1>
