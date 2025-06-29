# Calibre Ai Metadata Plugin
Artificial Intelligence Metadata Plugin for Calibre eBook Software

I had a problem, hundreds of thousands of out-of-print, rare and self-published books with no metadata.
I needed a way to complete all the metadata quickly. I decided to use Calibre, the eBook software, as it has the tools built in to embed metadata inside each document type, be it PDF, DOCX, EPUB.
It has built-in metadata plugins that retrieve metadata from Google, Goodreads, Amazon, etc.
I ran it on my huge collection of eBooks. About 30% of them came back with the correct metadata, which was a start.
So I ran a Google search to see how I could go about completing the other 70% of my library's missing metadata.
The response I received was that I would have to either:

A) Do it all by Hand. Read each book and then type the information into each field.
B) Use a Regex plugin and try to Regex match the titles.

How could you regex the information for such a large library? It would be impossible. But I gave it a try, it fell at the first hurdle, and it either returned nothing or random information.
Plus, you can't summarise a book with RegEx?

It took me about 10 days to research and complete the metadata for 100 eBooks. I worked out that at that rate, it would have taken me 842 years to complete the metadata by hand.

I had used Local AI in my Day job. So I thought, why can't I use Calibre to feed each book into a LocalLLM RAG system and get it to read the book and retrieve the information?
So in my spare time, I embarked on developing a plugin for Calibre to do just that.

When the plugin was close to completion, I ran a few tests to check the results. They were great, in fact better than great; they were perfect for my needs.

I set the plugin processing by just clicking the "Go" button and waited for a few days. My whole library and all of the metadata were now fully completed, Title, Author, Publication Date, Publisher, Genre, including a summary of the book's content written by the AI.

I thought, this is great, and others may find this useful. I would share it with the community. It may be useful for Businesses, Research students, Education establishments, etc.
Because it doesn't have to be just eBooks, using the AI, you can organise, dedupe and embed metadata into any document using Calibre.

You can organise Invoices, Research Papers, Tutor Notes, Love Letters, Utility bills, the list is endless. If the document has writing and is in a document format. 
It can be organised with Calibre using this AI Metadata plugin.

So hopefully you find this plugin as useful as I did.
