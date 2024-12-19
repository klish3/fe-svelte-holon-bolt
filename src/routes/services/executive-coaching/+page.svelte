<script lang="ts">
  import ServiceHeader from '$lib/components/ServiceHeader.svelte';
</script>

<svelte:head>
  <title>Executive Coaching - Holon Management Consulting</title>
</svelte:head>

<div class="bg-white py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <ServiceHeader
      title="Executive Coaching"
      description="Empower your leadership team with personalized executive coaching services."
    />
    
    <div class="mx-auto mt-16 max-w-2xl lg:max-w-none">
      <div class="grid grid-cols-1 gap-8 lg:grid-cols-2">
        <div class="bg-gray-50 p-8 rounded-lg">
          <h3 class="text-xl font-semibold mb-4">Leadership Development</h3>
          <p class="text-gray-600">Enhance leadership capabilities through personalized coaching and development programs.</p>
        </div>
        <div class="bg-gray-50 p-8 rounded-lg">
          <h3 class="text-xl font-semibold mb-4">Performance Optimization</h3>
          <p class="text-gray-600">Improve executive performance through targeted coaching and strategic guidance.</p>
        </div>
      </div>
    </div>
  </div>
</div>