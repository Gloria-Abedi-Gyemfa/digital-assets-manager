<template>
    <div class="flex justify-center items-center">
        <UiAuth class="w-2/5"/>
        <UiCard class="w-2/5 self-center">
            <div>
                <h4 class="text-heading text-center">{{ loginTitle }}</h4>
            <Input label="Email" type="email" placeholder="you@company.com"/>
            <Input label="Password" type="password" placeholder="Creat a password"/>
            <UiButton text="Login"/>
            <div class="my-2">
                <p class="text-center">{{authPageAlt}}</p>
            </div>
            <div class="flex justify-between">
                <button class="border py-1 px-4 rounded-lg">Google</button>
                <button class="border py-1 px-4 rounded-lg">Microsoft</button>
            </div>
        </div>
        </UiCard>
    </div>
</template>

<script lang="ts" setup>
import { authPageAlt, loginTitle} from '~/lib/auth';



</script>

<style>

</style>