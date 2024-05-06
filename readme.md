# simulacrum
a project to generate synthetic people with vivid backstories, equip them with human-like memory, and allow them to converse with each other in simulations. 
# Person Generation:
used long context models to make detailed "backstories" of agents, memories, personal relationships, motivations. Example: <br />
Input into person generation:  <br />
>{Name: Shawn Briar, Age: 24, Born: June 6, 1994, Locale Born: Union Springs, Alabama, USA, Locale Current: Union Springs, Alabama, USA, Languages: ['English'], Race: White, Gender Identity: Cisgender male, Historical Income: Low, Current Income: Low, Marital Status: Single, Kids: 1, Highest Education: 11th grade, {'openness': 'Low', 'conscientiousness': 'High', 'extraversion': 'Low', 'agreeableness': 'High', 'neuroticism': 'Low'}} <br />
Output: Childhood (age 0 to 12) <br />
>Major Arc: Shawn Briar's childhood in Union Springs, Alabama, was marked by a series of events and conditions that shaped his early life, deeply influenced by his family's low-income status and the rural setting of his hometown. Growing up, Shawn's family struggled financially, which often meant that luxuries were scarce and necessities sometimes hard to come by. This economic hardship fostered a sense of responsibility and conscientiousness in Shawn from a young age. He learned the value of hard work and the importance of taking care of his belongings and those around him. His high level of conscientiousness was evident in his approach to chores and responsibilities at home, where he often took the initiative to help out without being asked..... <br />
....
>5. **Mr. Daniels - Elementary School Principal**: Mr. Daniels passed away unexpectedly when Shawn was in the sixth grade. Known for his kind demeanor and fair approach to discipline, Mr. Daniels was a respected figure in Shawn's early education. When Shawn thinks about Mr. Daniels, he remembers feeling safe and valued at school, knowing there was an authority figure who genuinely cared. Mr. Daniels' absence affects Shawn by introducing him to the concept of mortality and the impact of leadership on a community's sense of security and belonging. <br />
>Beliefs Added: Shawn Briar's childhood, deeply influenced by his family's financial struggles and the close-knit community of Union Springs, Alabama, has instilled in him a set of core values centered around hard work, resilience, and the importance of community and family support. His high conscientiousness and agreeableness, coupled with his experiences of economic hardship and the support he received from family and community members, have led Shawn to value the collective well-being over individual success. This has likely fostered a belief in the importance of helping others and giving back to the community that supported him during tough times. Politically, these experiences may incline Shawn towards policies and leaders who advocate for social support systems and community development initiatives, reflecting his understanding of the challenges faced by low-income families. His low openness suggests a preference for traditional values and skepticism towards radical changes, which could translate into a conservative approach to social and economic policies, valuing stability and gradual improvement over rapid transformation.
.......... <br />
This goes on and on (checkout person1.txt).  <br />

Example simulated chat between two such agents (person1.txt and person2.txt): <br />
>Shawn: *waves* Hey there, neighbor! I don't think we've officially met. I'm Shawn Briar. I just moved here from Union Springs, Alabama. It's quite a change from the small town life I'm used to. <br />
>Dev: *smiles* Nice to meet you, Shawn! I'm Dev Seth. I recently moved to Boston from Mumbai, India. It's a pleasure to have you in the neighborhood. What brings you to the city? <br />
>Dev: That's great, Shawn! Congratulations on your GED and the new job. As for me, I'm actually here to start my own business. I've always been interested in entrepreneurship and innovation, ever since I participated in a business competition back in high school. I decided it was time to take the leap and pursue my dreams. <br />
>Shawn: *nods impressively* Starting your own business? That's a big deal. I remember doing a few odd jobs and working with my dad on handyman projects back home, but nothing like running a company. You must have a lot of drive and determination...... <br />
goes on and on. Agents perform well wrT memory retreival and retention. 
 <br />
here is a slide from a presentation I made showcasing what I am up to with the memory system at play here:
<img width="818" alt="Screenshot 2024-05-06 at 1 07 59 AM" src="https://github.com/prbsth/simulacrum/assets/34644276/146647ee-ddec-4431-aea1-469729a165c4">

here are some of the prelimanary results tested on scenarios taken from park et al, comparing their agent to mine:
<img width="584" alt="image" src="https://github.com/prbsth/simulacrum/assets/34644276/3175014b-3fcc-43a1-85a6-fb8ccd5441f8">
<img width="820" alt="image" src="https://github.com/prbsth/simulacrum/assets/34644276/075d3242-59cb-49ff-a0a7-66d333e53fbc">

Note that I am still working on some aspects of this system and I think my results will improve. 
