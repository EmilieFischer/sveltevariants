<script>
	import Button from "./Button.svelte";
	import Badge from "./Badge.svelte";
	import Footer from "./Footer.svelte";
	import Card from "./Card.svelte";
	import Inbox from "./Inbox.svelte";
	import Avatar from "./Avatar.svelte";
</script>

<h1>1. BUTTON COMPONENTS:</h1>
<section>
<article>
<h3>Default Button:</h3>
<Button>DEFAULT</Button>
<pre><code>{'<Button>DEFAULT</Button>'}</code></pre>
</article>

<article>
<h3>Primary Button:</h3>
<Button type="primary">PRIMARY</Button>
<pre><code>{'<Button type="primary">PRIMARY</Button>'}</code></pre>
</article>
<!-- <Button type="primary" mode="inversed">Første knap inversed</Button> -->


<article>
	<h3>Secondary Button:</h3>
<Button type="secondary">SECONDARY</Button>
<pre><code>{'<Button type="secondary">SECONDARY</Button>'}</code></pre>
</article>
<!-- <Button type="secondary" mode="inversed">Anden knap inversed</Button> -->

<article>
	<h3>Accent Button:</h3>
<Button type="accent">ACCENT</Button>
<pre><code>{'<Button type="accent">ACCENT</Button>'}</code></pre>
</article>

<article>
	<h3>Ghost Button:</h3>
<Button type="ghost">GHOST</Button>
<pre><code>{'<Button type="ghost">GHOST</Button>'}</code></pre>

</article>
<article>
<h3>Link Button:</h3>
<Button type="link">LINK</Button>
<pre><code>{'<Button type="link">LINK</Button>'}</code></pre>
</article>

</section>



<h1>2. BADGE COMPONENTS:</h1>
<section>
	<article>
		<h3>Default badge:</h3>
<Badge type="default">default</Badge>
<pre><code>{'<Badge type="default">default</Badge>'}</code></pre>
</article>

<article>
	<h3>Primary badge:</h3>
<Badge type="primary">primary</Badge>
<pre><code>{'<Badge type="primary">primary</Badge>'}</code></pre>
</article>

<article>
	<h3>Secondary badge:</h3>
<Badge type="secondary">secondary</Badge>
<pre><code>{'<Badge type="secondary">secondary</Badge>'}</code></pre>
</article>

<article>
	<h3>Accent badge:</h3>
<Badge type="accent">accent</Badge>
<pre><code>{'<Badge type="accent">accent</Badge>'}</code></pre>
</article>

<article>
	<h3>Ghost badge:</h3>
<Badge type="ghost">ghost</Badge>
<pre><code>{'<Badge type="ghost">ghost</Badge>'}</code></pre>
</article>
</section>

<h1>3. FOOTER COMPONENT:</h1>
<section>
	<article>
	<Footer/>
	<h3>Footer documentation:</h3>
		<pre><code>{'<Footer/>'}</code></pre>

</article>
</section>

<h1>4. CARD COMPONENT:</h1>

<section>
	<article>
		<Card/>
		<h3>Card documentation:</h3>
			<pre><code>{'<Card/>'}</code></pre>
	</article>
</section>

<h1>5. BUTTON WITH BADGE COMPONENT:</h1>

<section>
	<article>
		<Inbox/>
		<h3>Inbox documentation:</h3>
			<pre><code>{'<Inbox/>'}</code></pre>
	</article>
</section>

<h1>6. AVATAR WITH INDICATOR:</h1>

<section class="flex_container">
	<Avatar type="big" image="false">K</Avatar>
	<Avatar type="medium" mode="indicator">JO</Avatar>
	<Avatar type="small" image="false">MX</Avatar>
	<Avatar type="smallest" mode="indicator">AA</Avatar>
</section>

<hr>
<section>
	<article>
	<Avatar type="big" image="false">K</Avatar>
		<h3>Big:</h3>
	<pre><code>{'<Avatar size="big" image="false">K</Avatar>'}</code></pre>
	</article>

	<article>
		<Avatar type="medium" mode="indicator">JO</Avatar>
			<h3>Medium:</h3>
		<pre><code>{'<Avatar size="medium" mode="indicator">JO</Avatar>'}</code></pre>
		</article>

		<article>
			<Avatar type="small" image="false">MX</Avatar>
				<h3>Small:</h3>
			<pre><code>{'<Avatar size="small" image="false">MX</Avatar>'}</code></pre>
			</article>

			<article>
				<Avatar type="smallest" mode="indicator">AA</Avatar>
					<h3>Smallest:</h3>
				<pre><code>{'<Avatar size="smallest" mode="indicator">AA</Avatar>'}</code></pre>
				</article>
</section>

<style>
	.flex_container {
        display: flex;
		gap: 1rem
    }
</style>
