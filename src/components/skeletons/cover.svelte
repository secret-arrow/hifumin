<div class="flex flex-col w-full gap-2">
    <div
        class="relative w-full overflow-hidden rounded-lg mb-2 {$$props.class}"
    >
        <div class="absolute flex justify-center items-center w-full h-full">
            <slot />
        </div>
        <div class="w-full pb-[144.47%] bg-gray-50 dark:bg-gray-600" />
    </div>
    <div class="w-full h-6 rounded bg-gray-50 dark:bg-gray-600" />
    <div class="w-3/4 h-4 rounded bg-gray-50 dark:bg-gray-600" />
</div>
