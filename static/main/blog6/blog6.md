
<div class="image-container">
    <img src="/static/main/blog6/1.png" alt="QR Code" >
  </div>


<p>All Large Language Models (LLMs) are trained on an extensive range of tokens, reaching into the billions, if not trillions. The text utilized for training LLMs is not curated; it is scraped from the Internet and encompasses everything – accurate information, misinformation, lies, hate speech, and more. Using this vast dataset, LLMs are trained to predict the next most probable token (for non-experts, consider a token as a word). Thus, LLMs predict the most probable word from a dataset that contains, quite literally, everything, including a substantial amount of unreliable information. Reinforcement Learning from Human Feedback (RLHF) has significantly enhanced LLMs' accuracy and reduced hallucinations, but it cannot eliminate them entirely. </p>

<p>Simply put, if the LLM is trained with everything, it will produce everything, including hallucinations.
What should one expect otherwise? 
<p>

<p>
Furthermore, many expect LLMs to be the “source” of truth. But what constitutes the source of truth? What determines right from wrong? Numerous subtle topics exist where right and wrong depend heavily on context, country, culture, and moral and ethical values. Different countries uphold different values, and ethical and moral values evolve over time. How, then, can one expect the LLM to produce the “truth”?
</p>

<p>
So, what is the solution?
</p>
<p>
The answer lies in retrieval-augmented generation (RAG) and similar approaches, where there is a dataset of your facts and knowledge, and the LLM provides answers based solely on your facts and knowledge. For example, you can input all your reports about AI that you have published, and the LLMs will produce answers based on this knowledge and nothing else. If you pose a question outside this domain knowledge, it will inform you that it doesn’t know the answer.</p>

<p>
Your facts and knowledge are unique to you, as a person, organisation, or even a country. You can integrate your values and norms into it.
</p>

<p>
I have built an MVP, offering Q&A on my reports on AI, and have published another <a href="https://blagojdelipetrev.com/blog/44/">blog  </a>about it. If you want access to the MVP (mininum viable product) send me an email to blagoj@bitt.solutions
</p>

<p>
If you plan to build systems like this for your organization and need help, please feel free to contact me on my email above.
</p>