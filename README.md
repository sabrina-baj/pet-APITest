  <h1>Postman API Collection for Pet API</h1>
      <p>This repository contains a Postman collection that demonstrates how to interact with an API through <strong>Create</strong>, <strong>Read</strong>, <strong>Update</strong>, and <strong>Delete (CRUD)</strong> operations. It also uses environment variables to manage API URL.</p>
    <h2>Overview</h2>
    <p>This Postman collection demonstrates basic <strong>CRUD operations</strong> using a sample API. It consists of four main requests:</p>
    <ul>
        <li><strong>Create</strong> - Adds a new resource</li>
        <li><strong>View</strong> - Retrieves details of an existing resource</li>
        <li><strong>Update</strong> - Modifies an existing resource</li>
        <li><strong>Delete</strong> - Removes a resource</li>
    </ul>
    <p>The collection utilizes <strong>environment variables</strong> to handle dynamic API values such as base URLs and authentication tokens.</p>
    <h2>Environment Variables</h2>
    <p>The collection uses the following environment variables. These variables can be set up in your Postman environment:</p>
    <table>
        <thead>
            <tr>
                <th>Variable Name</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>PetStore</td>
                <td>The base URL for the API</td>
            </tr>
        </tbody>
    </table>
    <h2>How to Set Up the Environment</h2>
         <ol>
            <li>In Postman, go to the <strong>Environments</strong> tab (gear icon on the top-right)</li>
            <li>Create a new environment with the variables listed above</li>
            <li>Add your API base URL and authentication token to the variables</li>
            <li>Select this environment while running the collection</li>
        </ol>
   <h2>Collection Overview</h2>
            <h3>Create Operation (POST)</h3>
        <ul>
            <li><strong>Request Name</strong>: Creating Different Pets</li>
            <li><strong>Method</strong>: POST</li>
            <li><strong>Description</strong>: Sends a request to create a new resource in the system</li>
        </ul>
        <h3>View Operation (GET)</h3>
        <ul>
            <li><strong>Request Name</strong>: Fetch Different Pets</li>
            <li><strong>Method</strong>: GET</li>
            <li><strong>Description</strong>: Fetches a resource using its ID</li>
        </ul>
        <h3>Update Operation (PUT)</h3>
        <ul>
            <li><strong>Request Name</strong>: Update Existing Pets</li>
            <li><strong>Method</strong>: PUT</li>
            <li><strong>Description</strong>: Updates an existing resource using its ID</li>
        </ul>
        <h3>Delete Operation (DELETE)</h3>
        <ul>
            <li><strong>Request Name</strong>: Delete Existing Pets</li>
            <li><strong>Method</strong>: DELETE</li>
            <li><strong>Description</strong>: Deletes a resource by its ID</li>
        </ul>
    <h2>Usage</h2>
          <h3>1. Import the Collection</h3>
        <p>You can import the collection by clicking the <strong>Import</strong> button in Postman and selecting the collection file (e.g., Creating Different Pets.postman_collection.json).</p>
        <h3>2. Set Environment Variables</h3>
        <p>Make sure the environment variables (PetStore) are correctly set before running the collection.</p>
        <h3>3. Run the Collection</h3>
        <p>You can run each request individually or use <strong>Collection Runner</strong> to execute the entire collection in sequence.</p>
        <h3>4. Verify Responses</h3>
        <p>Check the status codes and response bodies to ensure the operations are functioning as expected.</p>
       <h2>How to Import the Collection</h2>
        <ol>
            <li>Open <strong>Postman</strong></li>
            <li>Click the <strong>Import</strong> button (top-left)</li>
            <li>Choose <strong>File</strong> and select the Postman collection JSON file</li>
            <li>The collection will be imported into Postman and will be available for testing</li>
        </ol>
