<script>
	import '../app.css';
	import { FormatText } from '$utils/FormatText';
</script>

<div class="bg-red-500 p-4 text-white">
	<slot />
	{FormatText('Hello World')}
</div>
