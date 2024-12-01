<div class="container mx-auto bg-white p-6">
  <h1 class="mb-6 text-center text-3xl font-bold">Resume Builder</h1>

  <form class="rounded-lg bg-white p-6 shadow-lg">
    <h2 class="mb-4 text-xl font-semibold">Personal Information</h2>
    <div class="form-control mb-4">
      <label class="label" for="name">
        <span class="label-text">Full Name</span>
      </label>
      <input
        id="name"
        type="text"
        placeholder="John Doe"
        class="input input-bordered w-full"
      />
    </div>
    <div class="form-control mb-4">
      <label class="label" for="email">
        <span class="label-text">Email Address</span>
      </label>
      <input
        type="email"
        placeholder="example@example.com"
        class="input input-bordered w-full"
      />
    </div>
    <div class="form-control mb-4">
      <label class="label" for="phone">
        <span class="label-text">Phone Number</span>
      </label>
      <input
        id="phone"
        type="tel"
        placeholder="+1234567890"
        class="input input-bordered w-full"
      />
    </div>

    <h2 class="mb-4 text-xl font-semibold">Work Experience</h2>
    <div class="form-control mb-4">
      <label for="job-title" class="label">
        <span class="label-text">Job Title</span>
      </label>
      <input
        id="job-title"
        type="text"
        placeholder="Software Engineer"
        class="input input-bordered w-full"
      />
    </div>
    <div class="form-control mb-4">
      <label class="label" for="company">
        <span class="label-text">Company Name</span>
      </label>
      <input
        id="company"
        type="text"
        placeholder="Tech Corp"
        class="input input-bordered w-full"
      />
    </div>
    <div class="form-control mb-4">
      <label class="label" for="duration">
        <span class="label-text">Duration</span>
      </label>
      <input
        id="duration"
        type="text"
        placeholder="Jan 2020 - Dec 2023"
        class="input input-bordered w-full"
      />
    </div>

    <h2 class="mb-4 text-xl font-semibold">Education</h2>
    <div class="form-control mb-4">
      <label class="label" for="education">
        <span class="label-text">Degree</span>
      </label>
      <input
        id="education"
        type="text"
        placeholder="Bachelor's in Computer Science"
        class="input input-bordered w-full"
      />
    </div>
    <div class="form-control mb-4">
      <label class="label" for="university">
        <span class="label-text">Institution</span>
      </label>
      <input
        id="university"
        type="text"
        placeholder="University Name"
        class="input input-bordered w-full"
      />
    </div>
    <div class="form-control mb-4">
      <label class="label" for="graduation-year">
        <span class="label-text">Graduation Year</span>
      </label>
      <input
        id="graduation-year"
        type="text"
        placeholder="2023"
        class="input input-bordered w-full"
      />
    </div>

    <div class="form-control mb-4">
      <label class="label" for="skills">
        <span class="label-text">Skills</span>
      </label>
      <textarea
        id="skills"
        placeholder="e.g., JavaScript, Python, React, etc."
        class="textarea textarea-bordered w-full"
      ></textarea>
    </div>

    <div class="form-control">
      <a href="/choose-a-mentor/" class="btn btn-primary w-full">
        Generate Resume
      </a>
    </div>
  </form>
</div>
