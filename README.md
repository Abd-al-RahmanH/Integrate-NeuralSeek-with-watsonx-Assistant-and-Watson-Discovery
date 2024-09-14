# Integrating NeuralSeek with watsonx Assistant and Watson Discovery

NeuralSeek enhances search capabilities by integrating deep learning with **watsonx Assistant** and **Watson Discovery**. This integration allows users to leverage more sophisticated and accurate search results, offering a smarter and more efficient chatbot experience.

In this tutorial, we will guide you step-by-step on how to integrate **NeuralSeek** into your watsonx Assistant instance and connect it with Watson Discovery for improved search results.

---

## Prerequisites

Before proceeding with the integration, ensure you have the following requirements:

- An **IBM Cloud account** with watsonx Assistant and Watson Discovery services already set up.
- Access to the **NeuralSeek API Key** from the NeuralSeek dashboard.
- A basic understanding of watsonx Assistant and Watson Discovery configurations.

For detailed setup instructions of watsonx Assistant or Discovery, you can follow the [official IBM documentation](https://cloud.ibm.com/docs/watson-assistant).

---

## Estimated Time

The entire process should take approximately **30 minutes** to complete, depending on familiarity with IBM Watson services.

---

## Steps for Integration

### Step 1: Access watsonx Assistant

1. **Login** to your IBM Cloud account, and navigate to your **watsonx Assistant** instance.
2. On the watsonx Assistant dashboard, locate the **Actions** menu on the left-hand side.

   ![Watson Assistant Dashboard](link_to_image_1)

3. Under the **Skills** section, click on **Create a skill**.

   ![Create Skill](link_to_image_2)

4. Choose the language for your assistant and select the **Dialog skill** option. Then click **Create** to begin configuring the new skill.

   ![Dialog Skill Configuration](link_to_image_3)

### Step 2: Launch NeuralSeek

1. Once your dialog skill is created, go to the **Integrations** tab and choose **Launch NeuralSeek**.

   ![Launch NeuralSeek](link_to_image_4)

2. You will be prompted to input your **NeuralSeek API key**. This key allows watsonx Assistant to connect and utilize NeuralSeek’s deep-learning models.

3. Configure additional settings, such as keyword searches and query filtering, based on the needs of your assistant.

   ![API Key Configuration](link_to_image_5)

### Step 3: Adjust and Customize Search Criteria

1. In the **NeuralSeek settings** page, you will have several options to adjust search behavior:
   - **Search scope**: Limit the search to specific datasets or allow broad search across multiple sources.
   - **Keyword customization**: Set specific keywords to refine query results and deliver more accurate answers to the user.
   - **Result customization**: Choose how results should be displayed—based on relevance, accuracy, or recency.

2. After configuring these settings, click **Save** to finalize the integration.

   ![Search Configuration](link_to_image_6)

### Step 4: Testing NeuralSeek within watsonx Assistant

1. To verify that NeuralSeek has been integrated correctly, initiate a test query in watsonx Assistant.
2. Run sample interactions through the chatbot to confirm that NeuralSeek is improving search results. If the integration is successful, you should notice enhanced responses based on NeuralSeek’s deep-learning capabilities.

   ![Test NeuralSeek](link_to_image_7)

### Step 5: Connect Watson Discovery

1. Now, connect your watsonx Assistant with **Watson Discovery** for broader search capabilities.
   - In the **Integrations** tab of watsonx Assistant, locate the **Discovery** section.
   - Connect your Discovery instance to allow watsonx Assistant to query datasets managed within Watson Discovery.

   ![Watson Discovery Integration](link_to_image_8)

2. Watson Discovery will provide NeuralSeek access to relevant external and internal documents, enhancing your chatbot’s ability to pull information from multiple sources.

   ![Watson Discovery Setup](link_to_image_9)

### Step 6: Review Logs and Analytics

1. After completing the integration, use the **Logs** and **Analytics** features within watsonx Assistant to monitor how effectively NeuralSeek is performing.
   - Review user queries, responses, and how NeuralSeek processes search requests.
   - This data will help in adjusting your configuration to improve search accuracy further.

   ![Logs and Metrics](link_to_image_10)

### Step 7: Final Tweaks and Customization

1. Based on the performance data from watsonx Assistant, revisit the NeuralSeek settings to refine search accuracy, result ranking, and handling of specific user queries.
2. You can also update the **query expansion** or **filtering criteria** for more tailored responses to your audience.

   ![Final Adjustments](link_to_image_11)

---

## Conclusion

By integrating NeuralSeek with watsonx Assistant and Watson Discovery, you can dramatically improve the chatbot’s search capabilities. The deep-learning models provided by NeuralSeek will help your assistant deliver more accurate, faster, and contextually relevant search results to user queries.

---

For additional help, please refer to  

 

 

 

 
 
