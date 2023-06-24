<template>
    <div>
        <h1 class="text-lg font-semibold">
            Skills
        </h1>
        <hr class="h-[2px] my-4 bg-gray-500">
        <article class="flex flex-col gap-4">
            <div
                v-for="skill in skills"
                :key="skill.title"
            >
                <h1 class="text-base font-semibold">
                    {{ skill.title }}
                </h1>
                <ul class="list-disc list-inside">
                    <li
                        v-for="children in skill.children"
                        :key="children.title"
                    >
                        {{ children.title }}
                    </li>
                </ul>
            </div>
        </article>
    </div>
</template>

<script setup lang="ts">
    const skills = [
        {
            title: "Frontend",
            children: [
                { title: "JavaScript/Vue/Nuxt.js/React/Next.js" },
                { title: "Tailwindcss/Bootstrap" },
                { title: "HTML/CSS/SASS/LESS" },
                { title: "Blade/Twig/EJS/Freemarker" },
            ]
        },
        {
            title: "Backend",
            children: [
                { title: "PHP (Laravel, CodeIgniter, Symfony, Slim Framework)" },
                { title: "Node.js (Express, Adonis.js, Socket.io)" },
            ]
        },
        {
            title: "Database",
            children: [
                { title: "MySQL/MariaDB" },
                { title: "MongoDB" },
                { title: "Redis" },
                { title: "SQLite" },
            ]
        },
        {
            title: "Other",
            children: [
                { title: "CI/CD" },
                { title: "Git/Github/Azure Repos/GitLab" },
                { title: "Azure Pipelines/Github Actions/GitLab CI" },
                { title: "Code Review" },
                { title: "Build Library" },
            ]
        }
    ];
</script>
