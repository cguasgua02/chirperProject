<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2
                class="text-xl font-semibold leading-tight text-gray-800"
            >
                Dashboard
            </h2>
        </template>

        <div class="py-12">
            <div class="mx-auto max-w-7xl sm:px-6 lg:px-8">
                <div
                    class="overflow-hidden bg-white shadow-sm sm:rounded-lg"
                >
                    <div class="p-6 text-gray-900">
                        <article>
                            <h1> <a href="/post"> Presentación de Prueba Reporte BI </a> </h1>
                                <p> 
                                    <!-- indent a text-->
                                <iframe title="Reporte_Prueba" width="1024" height="760" src="https://app.powerbi.com/view?r=eyJrIjoiNmYxYzA5MTQtODE3ZC00ZWU0LWIxZjctYzk4ODQ5ZTQyOGY5IiwidCI6IjlmMTE5OTYyLThjNjItNDMxYy1hOGVmLWU3ZTBhNDJkMTFmYyIsImMiOjR9" frameborder="0" allowFullScreen="true"></iframe>
                                 </p>
                        </article>
                    </div>
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
