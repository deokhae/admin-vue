<template>
    <nav class="level">
        <div class="level-item has-text-centered">
            <div>
            <p class="title">admin</p>
            </div>
        </div>
        <div class="level-right">
            <div class="level-item">
                <NuxtLink v-if="$i18n.locale === 'en'" :to="`/ko/admin`" class="Header__Link" active-class="none" exact>
                    english
                </NuxtLink>
                <NuxtLink v-else :to="$route.fullPath.replace(/^\/[^\/]+/, '')" class="Header__Link" active-class="none" exact>
                    한국어
                </NuxtLink>
            </div>
        </div>
    </nav>
</template>
