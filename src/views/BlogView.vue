<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout copy.vue';
import Join from '@/components/JoinContent.vue';
import BlogContent from '@/components/Blog/BlogContent.vue';
import CategoryContent from '@/components/Blog/CategoryContent.vue';
</script>

<template>
    <MainLayout>
        <BlogContent />
        <div class="mb-8">
            <CategoryContent  />
        </div>
        <div class="mb-8">
            <Join />
        </div>
    </MainLayout>
</template>