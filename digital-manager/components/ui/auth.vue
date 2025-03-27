<template>
    <div>
      <div>
          <h2 class="text-heading">{{authPageTitle}}</h2>
          <p class="my-4">{{ authPageDescription }}</p>
          <div>
              <div>
                  <h6 class="font-bold">Enterprise-grade Security</h6>
                  <p>Bank-level encryption for your digital assets</p>
              </div>
          </div>
  
          <div class="my-4">
              <div>
                  <h6 class="font-bold">Smart Organization</h6>
                  <p>AI-powered categorization and tagging</p>
              </div>
          </div>
  
          <div>
              <div>
                  <h6 class="font-bold">Performance Analytics</h6>
                  <p>Track and optimize your asset performance</p>
              </div>
          </div>
      </div>
      <AuthLogin/>
      <AuthSignup/>
    </div>
  </template>
  
  <script lang="ts" setup>
  import { authPageDescription, authPageTitle } from '~/lib/auth';
  
  </script>
  
  <style>
  
  </style>