<head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Noto+Sans:wght@400;600;700&display=swap">
</head>

<script>
    export let icon_left;
    export let icon_right;
    export let page_title;
    export let page_subtitle;
</script>

<div id="page_title" class="w-screen mt-4 pt-16 pb-16 text-center flex flex-col lg:bg-no-repeat select-none lg:bg-cover lg:bg-center lg:bg-[url('/assets/header_img.png')] bg-[url('/assets/banner_background.png')]">
    <div class="flex justify-center">
        {@html icon_left}
        <h1 class="h1 font-medium px-4">{@html page_title}</h1>
        {@html icon_right}
    </div>
    <div class="flex justify-center py-4">
        <hr class="bg-primary-500 w-48 h-0.5">
    </div>
    <h4 class="h4 mx-16 lg:mx-72">{@html page_subtitle}</h4>
</div>

<style>
    h1, h4 {
        font-family: 'Poppins', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
</style>