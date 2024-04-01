<div class="image-container">
    <img src="/static/main/blog6/1.png" alt="QR Code" >
</div>

<h3>Project Objectives</h3>
<ul>
    <li>Optimize for MacBook Pro with the M2 processor and 16GB of RAM.</li>
    <li>Develop a chatbot using Langchain to sift through personal files for Q&A.</li>
    <li>Explore and evaluate various Large Language Models (LLMs).</li>
    <li>Implement <a href="https://github.com/facebookresearch/faiss">FAISS vector storage</a> for managing text embeddings with OpenAI's technology.</li>
    <li>Leverage a Retrieval chain to pinpoint relevant text passages.</li>
    <li>Summarize information from retrieved content for succinct answers.</li>
    <li>Design a user-friendly chat interface with Gradio.</li>
</ul>

<h3>A Deep Dive into Open Source LLMs for Private Q&A</h3>

<p>
    In my previous <a href="https://blagojdelipetrev.com/blog/44/"> posts </a>, I've shared my journey with the OpenAI API, specifically in building a Q&A application. Curiosity led me to the next challenge: could I achieve similar results using open source LLMs?
</p>

<p>
    Beginning with Google searches and inquiries to GPT-4, I hoped to uncover a straightforward guide. Unfortunately, my quest initially led me to a maze of clickbait with little substance.
</p>

<p>
    The potential for open source Q&A on private data is vast and could revolutionize organizational knowledge management. I've delved into the benefits and drawbacks in another <a href="https://blagojdelipetrev.com/blog/47/">blog </a>.
</p>

<p>
    Perseverance paid off when I returned to an old haunt: Kaggle. This platform was instrumental in my deep learning ventures, particularly in satellite image recognition using CNNs. Years after it guided me through the nuances of <a href="https://www.mdpi.com/2072-4292/11/8/907">deep learning for satellite image recognition</a>, Kaggle's comprehensive resources now paved the way for this new endeavor. It was here that I discovered a <a href="https://www.kaggle.com/code/acorn8/q-a-with-llms-harry-potter-mistral-hf-api">Jupyter notebook</a> that became the cornerstone of my project.
</p>

<p>
    My objective was clear: run the LLMs locally on my MacBook Pro. I was determined to gauge the performance of a 16GB RAM MacBook without external GPU/TPU resources.
</p>

<p>
    Adapting the source code for macOS was my first hurdle. I quickly realized that Conda was indispensable, leaving Virtualenv by the wayside for this complex endeavor.
</p>



<p>
    MacBook users, take note: the <a href="https://github.com/ggerganov/llama.cpp"> LlamaCpp library </a> is crucial. I was able to get the LLMs functioning on my device, but code modifications were necessary, particularly with embeddings, where I pivoted to OpenAI for simplicity.
</p>

<p>
    Gradio's Chat UI was the interface that brought this all together, delivering a user experience that was as familiar as it was functional, with little need for further refinement. Gradio delivered more than expected.
</p>

<div class="image-container">
    <img src="/static/main/blog6/2.png" alt="QR Code" >
</div>


<p>
    This exploration has not only highlighted the viability of constructing private Q&A systems using open source LLMs but has also showcased the unexplored potential that lies within the synergy of community-driven resources like Kaggle and the advancement of technology.
</p>

<p>
    For those looking to navigate the rich waters of private data with the guidance of open source LLMs, the journey has never been more accessible. If integrating such an AI solution into your organization is on the horizon, reaching out could be the first step toward tapping into a reservoir of untapped capability. 
</p>

<p>
<a href="https://github.com/deblagoj/Q-A-on-private-data-using-open-source-LLMs/tree/main"> Link to Jupyter notebook on GitHub  </a>.
</p>

<h3>Lessons Learned</h3>
<ul>
    <li><strong>Kaggle Continues to Excel</strong>: My journey reaffirmed Kaggle's status as an unparalleled resource. Its vibrant discussions and high-quality code contributions are unmatched, making it an essential destination for anyone keen on exploring AI and LLMs.</li>
    <li><strong>Mac Compatibility and LlamaCpp</strong>: The discovery of LlamaCpp was a game-changer for running LLMs on a MacBook. It proves that with the right tools, MacBooks can become powerful allies in AI development.</li>
    <li><strong>The Intuitive Gradio Interface</strong>: Gradio's interface was a joy to work with. Its simplicity and intuitiveness made it the perfect choice for creating a user-friendly chat UI.</li>
    <li><strong>Understanding Hardware Constraints</strong>: The MacBook Pro with 16GB RAM has its limitations. It handles 7B models with ease but struggles with the more demanding 13B models. This was a valuable lesson in assessing the capabilities of available hardware.</li>
    <li><strong>Model Performance Evaluation</strong>: In comparing different models, Mistral's 13B LLMs stood out, delivering outputs that clearly overshadowed the results from Llama's 7B models.</li>
</ul>

<div class="image-container">
    <img src="/static/main/blog6/3.png" alt="QR Code" >
</div>