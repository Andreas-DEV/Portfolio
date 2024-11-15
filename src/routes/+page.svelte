<script lang="ts">
    import '../app.css'
    import githubSvg from "$lib/media/github.svg"
    import linkedInSvg from "$lib/media/linkedin.svg"
    import projectsPng from "$lib/media/projects.png"
</script>

<main>
    <div class="" id="center">
        <div class="flex items-center gap-4">
            <img class="rounded-full p-[2px] border-2 border-[#333333] shadow-xl" src="https://placehold.co/150" alt="">
            <div class="text-[#454444]">
                <h1 class="text-4xl text-[#454444]">Halløj<span class="text-5xl">🙋‍♂️</span></h1>
                <h2 class="text-4xl mb-4">Jeg hedder Andreas!</h2>
                <span class="mt-5 text-xs font-bold rounded-full text-white px-2 py-2 bg-[#62bd51] shadow-md">#front-end</span>
                <span class="mt-5 text-xs font-bold rounded-full text-white px-2 py-2 bg-[#62bd51] shadow-md">#back-end</span>
            </div>

        </div>

        <div class="flex items-center justify-around mt-10">

            <div class="flex gap-2 items-center">
                <img class="w-[40px]" src={githubSvg} alt="">
                <a class="hover:underline" target="_blank" href="https://github.com/Andreas-DEV">Github</a>
            </div>
            <div class="flex gap-2 items-center">
                <img class="w-[40px]" src={linkedInSvg} alt="">
                <a class="hover:underline" target="_blank" href="https://github.com/Andreas-DEV">LinkedIn</a>
            </div>

            <div class="flex gap-2 items-center">
                <img class="w-[40px]" src={projectsPng} alt="">
                <a class="hover:underline" href="/projects">Projects</a>
            </div>
            
        </div>
        
    </div>

</main>

<style lang="postcss">
    #center {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
    }
</style>