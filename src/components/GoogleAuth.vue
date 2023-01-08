<script lang="ts" setup>
   import GoogleLogo from '../assets/google-icon.svg';
   import { getGoogleUrl } from '@/stores/getGoogleUrl';

    const from = '/';
</script>

<template>
    <div>
        <a :href="getGoogleUrl(from)">
            <img :src="GoogleLogo" alt="Google Logo" />
        </a>
    </div>
</template>