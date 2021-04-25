<script context="module">
	export const prerender = true;
</script>

<h1>SvelteKit + Netlify Forms demo</h1>
<p>View <a href="https://github.com/sw-yx/sveltekitnetlifyforms">https://github.com/sw-yx/sveltekitnetlifyforms</a> for source</p>

<!-- "/src/routes/test-form.svelte" -->
<form name="test" method="post" netlify>
    <input type="hidden" name="form-name" value="test" />
    <!-- <input type="text" name="bot-field" /> -->
    <p>
        <label>Your Name: <input type="text" name="name" /></label>
    </p>
    <p>
        <label>Your Email: <input type="email" name="email" /></label>
    </p>
    <p>
        <label>Message: <textarea name="message" /></label>
    </p>
    <p>
        <button type="submit">Send</button>
    </p>
</form>