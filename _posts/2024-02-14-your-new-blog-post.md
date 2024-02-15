## MSII Update 2
# Recommendations

The biggest takeaway from our research was the importance of data security. Although, in part, this was focused on our data handling, it also extended to the security of the individual's "digital will" from the eyes of loved ones (much like the contents of an actual will). Furthermore, when it comes to the handling of an individual's last wishes, having a digital, centralized place for these requests to be held was also an opinion which was expressed. This is where a "digital will" has a clear advantage over something on paper (it is easily accessible, and not easily lost). To produce a valuable product, we have to prioritize data security (both internally and externally - perhaps through "subsidiary passwords" and two-factor authentication). 

The next recommendation is on "ease of access." Multiple interviewees put a heavy emphasis on simplicity of use. This is especially important since the loved ones of the deceased user might have little to no experience with our application. We need to focus on designing something which is seamless and intuitive. 

Finally, we're putting forward a recommendation to include updated information on each social media's current "post mortem" policies. This is a later development (not included in our previous report), and came about because we realized that one of the common responses to our question on "do people in your circles discuss what happens to their accounts after death" was "no." If most individuals aren't engaging in conversations about what happens to their social media accounts after they pass away, it follows that they won't be aware of the post-mortem policies of individual social media accounts (or even that they exist). As a result, we are putting forward the recommendation that our app includes a section with updated policies detailing the current post mortem options offered by each social media platform. 

---

# Updated Task Examples

## Revised Task Example 1

George is a middle-aged man who uses social media on a semi-regular basis. When he passes away, he wants his son to send a simple private message to all his contacts detailing his passing, and then delete his account. Although he's close to his son, he doesn't want to give him access to his accounts while he is still alive (for privacy's sake). Although he's considered keeping this information on a piece of paper, he's afraid it might be misplaced or lost. What he really wants is some safe, secure way for his son to get access to all this information right after he passes away.


## Revised Task Example 2

Jo is a retired businessman who is keen on social media. Despite his age, he is remarkably active online, sharing his wisdom and connecting with friends and family. He loves his accounts so he decides that it will be inherited by his children. He is taking steps to draft a digital will, and this method could help him to assign the digital assets. He seeks a secure and straightforward way to draft a digital will that respects his wishes and safeguards his online persona for future generations. The application Jo wants to use has updated and comprehensive  information on the current post-mortem policies of various social media platforms. This feature enables him to make informed decisions on how each of his accounts should be handled after his passing.


## Revised Task Example 3

Joy is really sad about the passing of his father. In order to transfer his father's digital assets, Joy must write numerous emails to the different platforms asking for access. This includes submitting Joy’s death certificate and Joy’s ID, to verify his claim and authority to inherit the digital accounts. Many platforms are not responding or saying that Joy does not have the authority to access anything. Joy wants a solution where all of management and transfer of assets are centralized and simplified, minimizing the bureaucratic and emotional burden of such a challenging time. 

---

# Revision Summary

The revised task examples enhance the original narratives by prioritizing data security and privacy, underlining the necessity for secure methods to pass on digital assets without compromising privacy before death. They also emphasize ease of access and user friendliness, acknowledging that heirs might vary in their technical knowledge, thus advocating for intuitive solutions. The integration of social media post mortem policies is a new addition, aiding informed decision making on the future of social media accounts after the users passing.

These revisions address the cumbersome process faced by Joy in transferring digital assets by proposing a centralized solution, reducing the administrative and emotional burden during grief. Additionally, they expand the scope of digital assets beyond social media, recognizing the need for comprehensive digital estate planning that includes cryptocurrencies and other digital holdings, as highlighted in Joy's scenario.

---

# Prioritized List of Requirements

1. **Choice and Control Over Digital Presence**

   Participants desire specific actions for their digital accounts post-mortem, including   deletion or preservation for descendants, leaving some openness to descendants downloading content before the deletion.
2. **Data Security(not pretty focus on this but prioritized in real implementation)**
3. **Management of Photos**
   
   Photos are an important concern than messages for most of the participants. Where they might choose to leave the photos to their descendants rather than their messages.
4. **Management of Contacts**
There’s some participants thinking of contact list inheritance or sending out notifications or personalized messages post-mortem.

5. **Simplicity**
“Easy to use” is a leading code for design, considering the variety of users with different expertises in tech use. Suggesting a similar mental model with a traditional paper wills.

---

# Design Alternatives

Discussion on different design alternatives, their pros and cons, and the decision to pursue a more user-friendly and legally compliant solution.


# Design Alternative 1

A certification authorized by the government which descendents could take it to the corresponding account company to inherit the account.

![Alternative Design 1](../Image/MSII Update 2/alter_2.jpg)

**Pros**

- If recognized by law, this can streamline the process of transferring digital assets.
- A universal system might make it easier for companies to have a consistent process for transferring accounts.
- Having this physical document could clarify the intention of the deceased, minimizing disputes among potential heirs.
- The expiration date suggests periodic updates which ensure the information is still in the latest version.

**Cons**
- The physical certificates can be forged, potentially leading to fraudulent claims.
- Different jurisdictions have different laws governing digital assets, which could complicate the implementation of a single system.
- In the event of sudden death, accessing the certificate might be difficult if it's kept in a secure or unknown location by the account holder.

---

# Design Alternative 2

An account verification tool similar to DUO to get verification every time an account is related to the tool, and there is a feature that no one can access to any connected account after passing by.

![Alternative Design 2](../Image/MSII Update 2/alter_1.jpg)

**Pros**

- By requiring verification every time an account is accessed, it significantly reduces the risk of unauthorized access.
- Every access attempt is likely logged, making it easier to track unauthorized attempts and ensuring only legitimate accesses are made.
- The tool allows for specific permissions to be set for different users, providing flexibility in how digital assets are managed posthumously.


**Cons**
- Frequent verifications can be cumbersome and may deter users from using the platform as frequently.
- If the verification relies on secondary devices (like a smartphone), losing or damaging the device can prevent access.
- If one tool manages access for multiple platforms, a single point of failure could jeopardize security across all connected accounts.

We have to keep a balance between security and accessibility.

Even though both designs can manage the security of the account, there are additional legal concerns that arise. Therefore, due to these issues, we will not pursue either of those two options.

Another rough idea is like an integrated account management system, but however similar to the previous one,  it concerns more legal rights issues, so we did not move on that design. Since we act as the third party platform where we hold tons of personal information.

---

# Design Alternative 3

A website/app where users can log in to access their “digital will.”

![Login Page](../Image/MSII Update 2/lowfi_1.png)

Once logged in, users will have the option to select any of the active “social media accounts.” When they click on one, it’s profile will pop up on the right. This will include instructions on how the account should be dealt with, the username/password, any additional security information (two-factor authentication, etc.), and an updated summary of any procedures that specific social media platform has for individuals who pass away.

![Main Page](../../Image/MSII_Update_2/lowfi_2.png)

**Pros**

- simple/easy to use
- can easily add multiple levels of security (extra passwords to view passwords etc.)
- app can be easily downloaded on phone - or accessed as a website


**Cons**
- too simple? (do we need more features?)
