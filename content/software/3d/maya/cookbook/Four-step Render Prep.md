After preparing your render settings, performing this four-step render prep process can help ensure you're rendering exactly what you want, and prevent you from having to re-render segments that may not look correct. 

1. Playblast
	Playblasting will render out the selected viewport, allowing you to check for general motion, popping, and camera action in the fastest way possible.
		Tips:
			- Ensure that you have the camera you want to render active in the viewport, and the viewport is focused (you've recently clicked into it, or there's no other viewport active (4-view / 2-view))
			- Turn the render gate on so you have clear view of what is in frame and what is not
2. Select Hi-Res
	Render select hi-res stills to check for correct shading, lighting, etc. Use your best judgement about where to render.

3. Lo-res full render
	Perform a full-length low-res beauty pass render (something like 400 pixels wide). This should render VERY quickly and will serve as a quick check for problems that may be shader-related but only be visible at render time (such as smoothing, some popping, shader network issues, etc)

4. Full-res render
	Once the above have all been completed, perform a full render!