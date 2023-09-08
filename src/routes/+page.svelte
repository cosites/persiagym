<script>
    let instagram = "https://www.instagram.com/persiagym/";
    let whatsapp = "#";
    let email = "contact@persiagym.com";
    let phone = "+982122063872";
    let address = "https://goo.gl/maps/t5d4J3rej92Drshi9";
    let iconPath = "/logo.jpg";
</script>

<div class="text-center">
    <!-- Header Icon -->
    <div class="mb-8">
        <img src="{iconPath}" alt="PersiaGym Icon" class="w-32 h-32 mx-auto rounded-full border-8 border-black"/>
    </div>

    <!-- Link Boxes -->
    <div class="grid gap-5">
        <!-- Instagram -->
        <a href="{instagram}" target="_blank" class="block py-4 px-6 bg-black rounded-lg text-white">
            <i class="text-lg mr-1 sm:mr-2 fa-brands fa-instagram"></i>
            Gallery
        </a>

        <!-- WhatsApp -->
        <a href="{whatsapp}" target="_blank" class="block py-4 px-6 bg-black rounded-lg text-white">
            <i class="text-lg mr-1 sm:mr-2 fa-brands fa-whatsapp"></i>
            News
        </a>

        <div class="mx-5 my-3 w-52 text-neutral-700/80 dark:text-neutral-400
                justify-between">
            <a class="hover:text-neutral-100 duration-500 mx-3"
               href="{address}">
                <i class="fa-solid fa-location-dot bg-black rounded-full p-3"></i>
            </a>
            <a class="hover:text-neutral-100 duration-500 mx-3"
               href="tel:{phone}">
                <i class="fa-solid fa-phone bg-black rounded-full p-3"></i>
            </a>
            <a class="hover:text-black dark:hover:text-neutral-100 duration-500 mx-3"
               href="mailto:{email}">
                <i class="fa-solid fa-envelope bg-black rounded-full p-3"></i>
            </a>
        </div>

    </div>
</div>
