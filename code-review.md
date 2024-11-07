# Code Review

## Purpose

Code review are essentials for team growth, code quality and consistency. They provide opportunity to:
- Enhance skills and share knowledge within the team.
- Reinforce best practices and standards.
- Foster collaboration.

## Guidelines

- Set a right collaborative tone: code reviews should feel like constructive discussions, not judgments. Focus on the code, not the person, and use respectful, supportive language.
    - ❌ Avoid: `I don't think it's a good approach.` or `That's wrong.`
    - ✅ Try: `Have you considered trying…?` or `This approach might help… What do you think?`
- Explain the `Why`` behind suggestions: when suggesting changes, explain the benefit (e.g readability, performance, maintainability) to help the author understand the value.
    - ✅ Try: `This adjustment could improve performance by avoiding duplicate loops.`
- Encourage questions and open discussion: reviews are ideal for learning and clarifying decisions. Asking questions promotes a deeper understanding for everyone involved.
    - ✅ Try question: `Could you walk me through why you chose this approach?`
    - ✅ Try response: `I acknowledge your suggestion. However, this is a small development task with limited capacity. I’ve created a user story to refactor according to this approach.`
- Highlight positives: recognize and call out good practices. This motivates the author and reinforces techniques the team wants to adopt widely.
    - ✅ Try: `Good use of the strategy design pattern here; it makes the code easier to read and maintain.`
- Promote small, frequent pull requests: Encourage smaller PRs to keep reviews more manageable and allow for quicker feedback loops.
- Enrich and standardize review practices: Consistent, comprehensive guidelines for code reviews help align the team on quality standards. This standardization supports efficient reviews, shared understanding, and better maintainability over time.
- Offer live discussion for complex issues: Some topics, especially those involving significant refactoring or design, are easier to resolve through live discussion. Suggest a call if a conversation would clarify things faster.
    - ✅ Try: `Let's hop on a quick call to discuss this in more detail.`
    - ✅ Encourage: `We can discuss this approach during our next team retro to share lessons learned and best practices.`

## References

- [Best Practices for Code Reviews That Foster Team Collaboration](https://dev.to/balrajola/best-practices-for-code-reviews-that-foster-team-collaboration-1l4e)