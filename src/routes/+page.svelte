<svelte:head>
	<title>Lukas Lewandowski | QA Automation Engineer</title>
	<meta name="description" content="Personal page of Lukas Lewandowski, QA Automation Engineer" />
</svelte:head>

<main>
	<header>
		<h1>Lukas Lewandowski</h1>
		<p class="title">QA Automation Engineer</p>
		<div class="contact">
			<a href="mailto:lukas@example.com">lukas@example.com</a>
			<span>·</span>
			<a href="https://github.com/LukasLewandowski" target="_blank" rel="noopener">GitHub</a>
			<span>·</span>
			<a href="https://linkedin.com/in/lukasl" target="_blank" rel="noopener">LinkedIn</a>
		</div>
	</header>

	<section>
		<h2>About</h2>
		<p>
			Passionate QA Automation Engineer with experience in building robust test frameworks,
			CI/CD integrations, and ensuring software quality at scale.
		</p>
	</section>

	<section>
		<h2>Skills</h2>
		<ul class="skills">
			<li>Selenium / Playwright / Cypress</li>
			<li>Python / JavaScript / Java</li>
			<li>REST API Testing (Postman, RestAssured)</li>
			<li>CI/CD: GitHub Actions, Jenkins</li>
			<li>Docker & containerized test environments</li>
			<li>Performance testing: k6, JMeter</li>
		</ul>
	</section>

	<section>
		<h2>Projects</h2>
		<div class="projects">
			<div class="project">
				<h3>E2E Test Framework</h3>
				<p>Playwright-based end-to-end test suite with parallel execution and HTML reporting.</p>
			</div>
			<div class="project">
				<h3>API Test Suite</h3>
				<p>Python + pytest framework covering REST endpoints with contract and regression tests.</p>
			</div>
			<div class="project">
				<h3>CI/CD Quality Gate</h3>
				<p>GitHub Actions pipeline with automated test runs, coverage checks, and Slack alerts.</p>
			</div>
		</div>
	</section>
</main>

<style>
	:global(*, *::before, *::after) {
		box-sizing: border-box;
		margin: 0;
		padding: 0;
	}

	:global(body) {
		font-family: 'Segoe UI', system-ui, sans-serif;
		background: #0f172a;
		color: #e2e8f0;
		line-height: 1.6;
	}

	main {
		max-width: 720px;
		margin: 0 auto;
		padding: 3rem 1.5rem;
	}

	header {
		margin-bottom: 3rem;
		border-bottom: 1px solid #1e293b;
		padding-bottom: 2rem;
	}

	h1 {
		font-size: 2.5rem;
		font-weight: 700;
		color: #f8fafc;
	}

	.title {
		font-size: 1.2rem;
		color: #38bdf8;
		margin-top: 0.25rem;
	}

	.contact {
		margin-top: 1rem;
		display: flex;
		gap: 0.75rem;
		align-items: center;
		font-size: 0.95rem;
		color: #94a3b8;
	}

	.contact a {
		color: #94a3b8;
		text-decoration: none;
	}

	.contact a:hover {
		color: #38bdf8;
	}

	section {
		margin-bottom: 2.5rem;
	}

	h2 {
		font-size: 1.25rem;
		font-weight: 600;
		color: #38bdf8;
		text-transform: uppercase;
		letter-spacing: 0.05em;
		margin-bottom: 1rem;
	}

	p {
		color: #cbd5e1;
	}

	.skills {
		list-style: none;
		display: flex;
		flex-wrap: wrap;
		gap: 0.5rem;
	}

	.skills li {
		background: #1e293b;
		color: #94a3b8;
		padding: 0.35rem 0.85rem;
		border-radius: 9999px;
		font-size: 0.875rem;
		border: 1px solid #334155;
	}

	.projects {
		display: grid;
		gap: 1rem;
	}

	.project {
		background: #1e293b;
		border: 1px solid #334155;
		border-radius: 0.5rem;
		padding: 1.25rem;
	}

	.project h3 {
		font-size: 1rem;
		font-weight: 600;
		color: #f1f5f9;
		margin-bottom: 0.4rem;
	}

	.project p {
		font-size: 0.9rem;
		color: #94a3b8;
	}
</style>
