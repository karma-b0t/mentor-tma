<script>
  let selectedCount = 0;

  function toggleSelection(card) {
    if (card.classList.contains('bg-primary')) {
      card.classList.remove('bg-primary', 'text-white');
      selectedCount--;
    } else if (selectedCount < 3) {
      card.classList.add('bg-primary', 'text-white');
      selectedCount++;
    } else {
      alert('You can only select up to 3 mentors.');
    }
  }

  function submitSelection() {
    if (selectedCount === 0) {
      alert('Please select a mentor.');
    } else {
      alert('Your selection has been submitted!');
    }
  }
</script>

<div class="container mx-auto p-6">
  <h1 class="mb-6 text-center text-3xl font-bold">Choose A Mentor</h1>
  <p class="mb-8 text-center text-xl text-gray-600">
    Select a mentors to guide you. Click on their card to select.
  </p>

  <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 lg:grid-cols-3">
    <!-- Mentor Card 1 -->
    <a
      href="#"
      type="button"
      class="card cursor-pointer rounded-lg border border-gray-200 bg-white shadow-md transition hover:shadow-lg"
      onclick={toggleSelection()}
    >
      <div class="card-body">
        <h2 class="card-title">John Doe</h2>
        <p class="text-gray-600">Expertise: AI & Machine Learning</p>
        <p class="text-sm text-gray-500">
          Experience: 5+ years as an AI Researcher
        </p>
      </div>
    </a>

    <!-- Mentor Card 2 -->
    <div
      class="card cursor-pointer rounded-lg border border-gray-200 bg-white shadow-md transition hover:shadow-lg"
      onclick={toggleSelection()}
    >
      <div class="card-body">
        <h2 class="card-title">Jane Smith</h2>
        <p class="text-gray-600">Expertise: Full Stack Development</p>
        <p class="text-sm text-gray-500">
          Experience: 8+ years in web and mobile apps
        </p>
      </div>
    </div>

    <!-- Mentor Card 3 -->
    <div
      class="card cursor-pointer rounded-lg border border-gray-200 bg-white shadow-md transition hover:shadow-lg"
      onclick={toggleSelection()}
    >
      <div class="card-body">
        <h2 class="card-title">Alice Johnson</h2>
        <p class="text-gray-600">Expertise: Cloud Computing</p>
        <p class="text-sm text-gray-500">Experience: AWS Certified Architect</p>
      </div>
    </div>

    <!-- Mentor Card 4 -->
    <div
      class="card cursor-pointer rounded-lg border border-gray-200 bg-white shadow-md transition hover:shadow-lg"
      onclick={toggleSelection(this)}
    >
      <div class="card-body">
        <h2 class="card-title">Robert Brown</h2>
        <p class="text-gray-600">Expertise: Cybersecurity</p>
        <p class="text-sm text-gray-500">
          Experience: 10+ years in network security
        </p>
      </div>
    </div>

    <!-- Mentor Card 5 -->
    <div
      class="card cursor-pointer rounded-lg border border-gray-200 bg-white shadow-md transition hover:shadow-lg"
      onclick={toggleSelection()}
    >
      <div class="card-body">
        <h2 class="card-title">Emma Wilson</h2>
        <p class="text-gray-600">Expertise: UI/UX Design</p>
        <p class="text-sm text-gray-500">
          Experience: Designed for top tech companies
        </p>
      </div>
    </div>
  </div>

  <div class="mt-6 text-center">
    <button class="btn btn-primary" onclick={submitSelection()}
      >Confirm Selection</button
    >
  </div>
</div>
