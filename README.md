# Chatbot Overview and Limitations

## Learning Goals

- Discuss what an AI chat does and how it works.
- Discuss the limitations of AI chat bots.

## Introduction

ChatGPT has been all over the news lately. They grew to 100 millions users in
the span of 3 months and currently have over 1.5 billion visitors per month!
Several other tools such as Bard by Google, Bing Chat have been released as
well.

All of these tools are categorized as general-purpose AI chatbots. They are also
known as open-domain chatbots or conversational agents. These tools aim to
provide information across a vast array of subjects while simulating human
conversation.

## General-Purpose AI Chatbots

AI chatbots like ChatGPT generally use natural language processing and machine
learning techniques to understand user inputs, context, and generate responses.

They rely on large language models trained on vast amounts of data from the
internet. These chatbots can learn patterns, context, and language nuances from
the data which allows them to provide contextually relevant responses.

The conversational abilities makes these chatbots suited for applications where
human-like interactions are desired such as customer support and virtual
assistants. These companies provide APIs to interact with their model which
makes it fairly straightforward to integrate them into products. Although,
depending on the company, the chatbots may need to be trained on internal
(non-public) data before it’s ready to use.

[Khanmigo](https://support.khanacademy.org/hc/en-us/articles/14394953976333--Update-Introducing-Khanmigo-Khan-Academy-s-AI-Tool)
is a great implementation by Khan Academy. It’s an AI guide which aims to
provide a one-on-one tutoring experience for students. It can also help teachers
with administrative tasks.

## Limitations

Although, chatbots can be very helpful in certain cases, they have several
limitations. Some of the main limitations to be aware of are:

1. **“Hallucinations”**: Since chatbots use statistics to decide their responses
   instead of reasoning, they can respond with fake information. Moreover,
   chatbots will present both true and false information with the same level of
   confidence. For example, if you ask a chatbot to suggest a list of books on
   distributed systems, it might add a few fake titles with fake authors along
   with real books to the list. ChatGPT’s
   [FAQ](https://help.openai.com/en/articles/6783457-what-is-chatgpt) page
   mentions, “ChatGPT is not connected to the internet, and it can occasionally
   produce incorrect answers. It has limited knowledge of world and events after
   2021 and may also occasionally produce harmful instructions or biased
   content.”
2. **Lack of Context**: AI chatbots usually don’t retain context beyond the
   immediate conversation. Newer models can retain some context but generally
   they only use the context provided in the input to generate responses.
3. **Lack of Reasoning**: As discussed earlier, AI chatbots can’t reason about
   information. They are great at relaying factual information based on the
   provided data which is generally what you’d want to use them for. Further
   research is necessary once the chatbot provides you with any information.
4. **Privacy and Security Concerns**:
   [Several companies have banned the use of general AI chatbots](https://www.hr-brew.com/stories/2023/05/11/these-companies-have-banned-chatgpt-in-the-office)
   at their workplace due to privacy and security concerns. Some of these
   companies have developed or are developing in-house AI tools for their
   employees.
5. **Lack of Citation**: AI chatbots often don’t provide all the sources they
   used to generate their response. Some chatbots like ChatGPT don’t provide any
   sources in their response. This prevents people from validating the
   information provided by the chatbots.

Despite these limitations, AI chatbots can still be useful if used with care by
verifying the chatbot responses. According to the
[StackOverflow 2023 Survey](https://survey.stackoverflow.co/2023/#ai), about 58%
developers don’t trust the code or information generated chatbots. It’s better
to generate boilerplate code or prototype data instead of asking chatbots to
solve complex problems.

For early career engineers or people who are starting out with programming, it’s
recommended that they try to debug error codes on their own before consulting
external resources like search engines and chatbots. And they should not ask
chatbots to generate complex code since they may lack the experience to identify
when the code has issues. Here’s a short exchange that
[highlights how ChatGPT can give a wrong response](https://www.linkedin.com/posts/getify_where-do-i-send-my-invoice-for-teaching-activity-7005600563258146816-Vdg1?utm_source=share&utm_medium=member_desktop).

Always keep these limitations in mind when working with AI tools and
cross-reference the responses with official docs and external sources.

## Conclusion

General-purpose chatbots can be great tools for improving developer
productivity. However, they must be used very carefully by cross-referencing
their responses with official docs and other external sources.

## Resources

- [Introducing Khanmigo](https://support.khanacademy.org/hc/en-us/articles/14394953976333--Update-Introducing-Khanmigo-Khan-Academy-s-AI-Tool)
  by Khan Academy.
- [ChatGPT FAQ Page](https://help.openai.com/en/articles/6783457-what-is-chatgpt).
- [Companies that have Banned or Limited ChatGPT at Work](https://www.hr-brew.com/stories/2023/05/11/these-companies-have-banned-chatgpt-in-the-office).
- [StackOverflow 2023 Survey](https://survey.stackoverflow.co/2023/#ai).
