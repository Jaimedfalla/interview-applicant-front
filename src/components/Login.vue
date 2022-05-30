<template>
    <main class="container">
        <div class="form-container">
            <h1 class="title">Login</h1>
            <form @submit.prevent="login">
                <div class="field">
                    <label for="" class="label">Email</label>
                    <div class="control">
                        <input type="email" class="input" v-model="email" required>
                    </div>
                </div>
            </form>
        </div>
    </main>
</template>
<script setup lang="ts">

</script>