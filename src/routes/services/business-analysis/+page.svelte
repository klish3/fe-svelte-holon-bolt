<script lang="ts">
  import ServiceHeader from '$lib/components/ServiceHeader.svelte';
</script>

<svelte:head>
  <title>Business Analysis - Holon Management Consulting</title>
</svelte:head>

<div class="bg-white py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <ServiceHeader
      title="Business Analysis"
      description="Unlock insights and optimize operations with our comprehensive business analysis services."
    />
    
    <div class="mx-auto mt-16 max-w-2xl lg:max-w-none">
      <div class="grid grid-cols-1 gap-8 lg:grid-cols-2">
        <div class="bg-gray-50 p-8 rounded-lg">
          <h3 class="text-xl font-semibold mb-4">Process Analysis</h3>
          <p class="text-gray-600">Detailed analysis of business processes to identify inefficiencies and opportunities for improvement.</p>
        </div>
        <div class="bg-gray-50 p-8 rounded-lg">
          <h3 class="text-xl font-semibold mb-4">Requirements Engineering</h3>
          <p class="text-gray-600">Expert gathering and documentation of business requirements for successful project implementation.</p>
        </div>
      </div>
    </div>
  </div>
</div>