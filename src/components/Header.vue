<template>
    <header class="bg-gradient-to-r from-gray-500 to-primary-500 text-white">
        <div class="flex">
            <div class="flex-none">
                <img
                    class="h-56 w-56"
                    src="https://gitlab.com/uploads/-/system/user/avatar/658642/avatar.png"
                    alt="Profile Logo"
                >
            </div>

            <div class="flex justify-between py-6 p-8 flex-1">
                <div>
                    <h1 class="text-3xl font-semibold mb-2">
                        Andri Anto
                    </h1>
                    <h2 class="text-2xl">
                        Full Stack Developer
                    </h2>

                    <ul class="space-y-1 text-left mt-4">
                        <li class="flex items-center space-x-2">
                            <!-- Icon -->
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                class="flex-shrink-0 w-5 h-5"
                                fill="currentColor"
                            >
                                <title>email</title>
                                <path d="M20,8L12,13L4,8V6L12,11L20,6M20,4H4C2.89,4 2,4.89 2,6V18A2,2 0 0,0 4,20H20A2,2 0 0,0 22,18V6C22,4.89 21.1,4 20,4Z" />
                            </svg>

                            <span>
                                <a href="mailto:andrianto.ykhc@gmail.com">
                                    andrianto.ykhc@gmail.com
                                </a>
                            </span>
                        </li>

                        <li class="flex items-center space-x-2">
                            <!-- Icon -->
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                class="flex-shrink-0 w-5 h-5"
                                fill="currentColor"
                            >
                                <title>phone</title>
                                <path d="M6.62,10.79C8.06,13.62 10.38,15.94 13.21,17.38L15.41,15.18C15.69,14.9 16.08,14.82 16.43,14.93C17.55,15.3 18.75,15.5 20,15.5A1,1 0 0,1 21,16.5V20A1,1 0 0,1 20,21A17,17 0 0,1 3,4A1,1 0 0,1 4,3H7.5A1,1 0 0,1 8.5,4C8.5,5.25 8.7,6.45 9.07,7.57C9.18,7.92 9.1,8.31 8.82,8.59L6.62,10.79Z" />
                            </svg>


                            <span>
                                <a href="tel:+6282136523735">
                                    +6282136523735
                                </a>
                            </span>
                        </li>

                        <li class="flex items-center space-x-2">
                            <!-- Icon -->
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                class="flex-shrink-0 w-5 h-5"
                                fill="currentColor"
                            >
                                <title>map-marker</title>
                                <path d="M12,11.5A2.5,2.5 0 0,1 9.5,9A2.5,2.5 0 0,1 12,6.5A2.5,2.5 0 0,1 14.5,9A2.5,2.5 0 0,1 12,11.5M12,2A7,7 0 0,0 5,9C5,14.25 12,22 12,22C12,22 19,14.25 19,9A7,7 0 0,0 12,2Z" />
                            </svg>

                            <span>
                                Jl. Kedawung, Nologaten, Caturtunggal, Depok, Sleman, Yogyakarta, Indonesia
                            </span>
                        </li>
                    </ul>
                </div>

                <div>
                    <ul class="space-y-2 text-left">
                        <li class="flex items-center space-x-2">
                            <!-- Icon -->
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                class="flex-shrink-0 w-5 h-5"
                                fill="currentColor"
                            >
                                <title>linkedin</title>
                                <path d="M19 3A2 2 0 0 1 21 5V19A2 2 0 0 1 19 21H5A2 2 0 0 1 3 19V5A2 2 0 0 1 5 3H19M18.5 18.5V13.2A3.26 3.26 0 0 0 15.24 9.94C14.39 9.94 13.4 10.46 12.92 11.24V10.13H10.13V18.5H12.92V13.57C12.92 12.8 13.54 12.17 14.31 12.17A1.4 1.4 0 0 1 15.71 13.57V18.5H18.5M6.88 8.56A1.68 1.68 0 0 0 8.56 6.88C8.56 5.95 7.81 5.19 6.88 5.19A1.69 1.69 0 0 0 5.19 6.88C5.19 7.81 5.95 8.56 6.88 8.56M8.27 18.5V10.13H5.5V18.5H8.27Z" />
                            </svg>

                            <span>
                                <a
                                    href="https://linkedin.com/in/andripgbyk"
                                    target="_blank"
                                >
                                    linkedin.com/in/andripgbyk
                                </a>
                            </span>
                        </li>
                        <li class="flex items-center space-x-2">
                            <!-- Icon -->
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                class="flex-shrink-0 w-5 h-5"
                                fill="currentColor"
                            >
                                <title>github</title>
                                <path d="M12,2A10,10 0 0,0 2,12C2,16.42 4.87,20.17 8.84,21.5C9.34,21.58 9.5,21.27 9.5,21C9.5,20.77 9.5,20.14 9.5,19.31C6.73,19.91 6.14,17.97 6.14,17.97C5.68,16.81 5.03,16.5 5.03,16.5C4.12,15.88 5.1,15.9 5.1,15.9C6.1,15.97 6.63,16.93 6.63,16.93C7.5,18.45 8.97,18 9.54,17.76C9.63,17.11 9.89,16.67 10.17,16.42C7.95,16.17 5.62,15.31 5.62,11.5C5.62,10.39 6,9.5 6.65,8.79C6.55,8.54 6.2,7.5 6.75,6.15C6.75,6.15 7.59,5.88 9.5,7.17C10.29,6.95 11.15,6.84 12,6.84C12.85,6.84 13.71,6.95 14.5,7.17C16.41,5.88 17.25,6.15 17.25,6.15C17.8,7.5 17.45,8.54 17.35,8.79C18,9.5 18.38,10.39 18.38,11.5C18.38,15.32 16.04,16.16 13.81,16.41C14.17,16.72 14.5,17.33 14.5,18.26C14.5,19.6 14.5,20.68 14.5,21C14.5,21.27 14.66,21.59 15.17,21.5C19.14,20.16 22,16.42 22,12A10,10 0 0,0 12,2Z" />
                            </svg>

                            <span>
                                <a
                                    href="https://github.com/andripgbyk"
                                    target="_blank"
                                >
                                    github.com/andripgbyk
                                </a>
                            </span>
                        </li>
                        
                        <li class="flex items-center space-x-2">
                            <!-- Icon -->
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                class="flex-shrink-0 w-5 h-5"
                                fill="currentColor"
                            >
                                <title>gitlab</title>
                                <path d="M21.94 13.11L20.89 9.89C20.89 9.86 20.88 9.83 20.87 9.8L18.76 3.32C18.65 3 18.33 2.75 17.96 2.75C17.6 2.75 17.28 3 17.17 3.33L15.17 9.5H8.84L6.83 3.33C6.72 3 6.4 2.75 6.04 2.75H6.04C5.67 2.75 5.35 3 5.24 3.33L3.13 9.82C3.13 9.82 3.13 9.83 3.13 9.83L2.06 13.11C1.9 13.61 2.07 14.15 2.5 14.45L11.72 21.16C11.89 21.28 12.11 21.28 12.28 21.15L21.5 14.45C21.93 14.15 22.1 13.61 21.94 13.11M8.15 10.45L10.72 18.36L4.55 10.45M13.28 18.37L15.75 10.78L15.85 10.45H19.46L13.87 17.61M17.97 3.94L19.78 9.5H16.16M14.86 10.45L13.07 15.96L12 19.24L9.14 10.45M6.03 3.94L7.84 9.5H4.23M3.05 13.69C2.96 13.62 2.92 13.5 2.96 13.4L3.75 10.97L9.57 18.42M20.95 13.69L14.44 18.42L14.46 18.39L20.25 10.97L21.04 13.4C21.08 13.5 21.04 13.62 20.95 13.69" />
                            </svg>

                            <span>
                                <a
                                    href="https://gitlab.com/andripgbyk"
                                    target="_blank"
                                >
                                    gitlab.com/andripgbyk
                                </a>
                            </span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>

<script setup lang="ts"></script>
