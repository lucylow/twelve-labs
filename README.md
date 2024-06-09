# INFINITE JEST

Gateway to an endless world of movie and TV show insights, where every question unlocks a universe of cinematic knowledge.

![](https://github.com/lucylow/twelve-labs/blob/main/Screen%20Shot%202024-06-09%20at%2011.03.58%20AM.png?raw=true)



### Example: Deadpool & Wolverine 

Movie Trailer: 
https://www.youtube.com/watch?v=73_1biulkYk

![](https://deuqpmn4rs7j5.cloudfront.net/66649f09937ce44a0402bad4/66659a3efa7835326810120c/thumbnails/fd31bdd0-eaf4-427f-bc27-6cb7939e6249.0000001.jpg)


### HOW IT WORKS 

1. **Ingest Video and Create Embeddings:**
   - The trailer is uploaded to the Twelve Labs platform.
   - The platform processes the video, creating embeddings that capture visual, audio, textual, and conversational data.

2. **Store Embeddings in Vector Database:**
   - The embeddings are stored in a vector database like Pinecone for efficient retrieval.
   - Each embedding is indexed with relevant metadata (e.g., timestamps, scene descriptions).

3. **User Query Processing:**
   - The chatbot receives the user's query (e.g., "Tell me about Deadpool's first appearance in the trailer").
   - The query is processed using natural language understanding (NLU) to determine the intent and extract key terms.

4. **Retrieve Relevant Video Embeddings:**
   - The system queries the vector database to find the most relevant video segments based on the user's query.
   - For example, it retrieves the embedding corresponding to Deadpool's first appearance.

5. **Generate Response:**
   - The retrieved embeddings are used as context to generate a coherent and informative response.
   - The system utilizes a language model (e.g., GPT) to create a response that incorporates details from the video embedding.

6. **Deliver Response to User:**
   - The chatbot presents the generated response to the user, providing accurate and contextually relevant information.



### Embedded Video 
"""
VIDEO ID: 66659a48d22b3a3c97bf1d5f
{'_id': '66659a3efa7835326810120c',
 'created_at': '2024-06-09T12:04:14.069Z',
 'estimated_time': '2024-06-09T12:07:40.728Z',
 'hls': {'status': 'COMPLETE',
         'thumbnail_urls': ['https://deuqpmn4rs7j5.cloudfront.net/66649f09937ce44a0402bad4/66659a3efa7835326810120c/thumbnails/fd31bdd0-eaf4-427f-bc27-6cb7939e6249.0000001.jpg'],
         'updated_at': '2024-06-09T12:04:59.781Z',
         'video_url': 'https://deuqpmn4rs7j5.cloudfront.net/66649f09937ce44a0402bad4/66659a3efa7835326810120c/stream/fd31bdd0-eaf4-427f-bc27-6cb7939e6249.m3u8'},
 'index_id': '666599d4e6fb7df29de0f89c',
 'metadata': {'duration': 159,
              'filename': 'Deadpool & Wolverine | Official Trailer | In '
                          'Theaters July 26',
              'height': 720,
              'width': 1280},
 'status': 'ready',
 'type': 'index_task_info',
 'updated_at': '2024-06-09T12:08:52.222Z',
 'video_id': '66659a48d22b3a3c97bf1d5f'}
 """


### Example: SEARCH

**Find any scene in natural language**
- **User Query:** "Show me Deadpool's first appearance in the trailer."
  - **Response:** The system retrieves the clip where Deadpool first appears on screen.

- **User Query:** "Find the scene where Deadpool fights Wolverine."
  - **Response:** The system retrieves the specific moments in the trailer where Deadpool and Wolverine are engaged in a fight.

### Example: GENERATE

**Generate any text about your video through prompting**
- **Generate Summary:**
  - **User Prompt:** "Generate a summary of the Deadpool & Wolverine trailer."
  - **Response:** "The trailer introduces Deadpool and Wolverine, highlighting their conflict and humorous interactions. The action-packed scenes are interspersed with witty banter and dramatic moments."

- **Generate Highlights:**
  - **User Prompt:** "Create highlights for the Deadpool & Wolverine trailer."
  - **Response:** "1. Deadpool's first appearance. 2. Wolverine's dramatic entrance. 3. The epic fight between Deadpool and Wolverine. 4. Deadpool's witty remark about Wolverine's claws."

### Example: CLASSIFY

**Classify all of your content in seconds**
- **Categories:**
  - **Action:** Classify scenes with high-intensity action, such as fights or explosions.
  - **Comedy:** Classify humorous scenes, especially those with Deadpool's jokes and witty remarks.
  - **Drama:** Classify dramatic moments, such as emotional dialogues or intense standoffs.

**Specific Examples:**
- **Action:**
  - **Scene:** Deadpool and Wolverine's fight scene.
  - **Classification:** This scene is tagged under the "Action" category.

- **Comedy:**
  - **Scene:** Deadpool making a witty remark about Wolverine's claws.
  - **Classification:** This scene is tagged under the "Comedy" category.

- **Drama:**
  - **Scene:** Wolverine's dramatic entrance.
  - **Classification:** This scene is tagged under the "Drama" category.
 


### Example: RAG Chatbot for "Deadpool & Wolverine" Trailer

**User Interaction with the Chatbot**

**User:** "Tell me about Deadpool's first appearance in the trailer."

**Chatbot Response:**
"Deadpool's first appearance in the trailer occurs around the 15-second mark. He makes a dramatic entrance with his signature red suit and mask, immediately engaging in witty banter."

**User:** "What happens during the fight between Deadpool and Wolverine?"

**Chatbot Response:**
"The fight between Deadpool and Wolverine is intense and action-packed. It starts at approximately the 1:20 mark of the trailer. Deadpool uses his agility and humor to taunt Wolverine, while Wolverine relies on his brute strength and claws. The fight features fast-paced choreography, sharp dialogue, and ends with a humorous quip from Deadpool about Wolverine's claws."

**User:** "Summarize the main plot of the Deadpool & Wolverine trailer."

**Chatbot Response:**
"The 'Deadpool & Wolverine' trailer introduces a thrilling clash between the two iconic characters. It highlights Deadpool's irreverent humor and Wolverine's brooding intensity. The trailer showcases several action scenes, including an epic fight between the two, while also hinting at an underlying plot involving a new threat they must face together. The combination of humor, action, and character dynamics promises an exciting and entertaining movie."

**User:** "What are some funny moments in the trailer?"

**Chatbot Response:**
"There are several funny moments in the trailer:
1. Deadpool makes a sarcastic comment about Wolverine's claws during their fight, saying, 'Nice manicure, did you get those done at a salon?'
2. Deadpool's dramatic entrance is followed by a quip about his costume being 'freshly laundered.'
3. In a brief scene, Deadpool tries to annoy Wolverine by imitating his growling voice and stance, leading to a comical exchange."



