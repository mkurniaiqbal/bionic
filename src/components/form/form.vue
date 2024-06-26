<template>
<div class="container mt-5">
        <h2>Send Your Job Application</h2>
        <form>
            <div class="row">
                <div class="form-group col-md-6">
                    <label for="inputName">Your Name</label>
                    <input type="text" class="form-control" id="inputName" placeholder="Enter your name">
                </div>
                <div class="form-group col-md-6">
                    <label for="inputMobile">Mobile Number</label>
                    <input type="text" class="form-control" id="inputMobile" placeholder="Enter your mobile number">
                </div>
            </div>
            <div class="row">
                <div class="form-group col-md-6">
                    <label for="inputEmail">Email Address</label>
                    <input type="email" class="form-control" id="inputEmail" placeholder="Enter your email">
                </div>
                <div class="form-group col-md-6">
                    <label for="inputMessage">Write your message here...</label>
                    <textarea class="form-control" id="inputMessage" placeholder="Write your message" rows="1"></textarea>
                </div>
            </div>
            <br>
            <div class="form-group">
                <label>File</label>
                <br>
                <label class="custom-file-upload">
                    <input type="file" id="inputFile">
                    <span class="icon">&#x1F4E4;</span> <!-- Optional icon -->
                </label>
            </div>
            <br>

            <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
    </div>
</template>

<style scoped>
    .custom-file-upload {
            display: inline-block;
            padding: 12px 24px;
            cursor: pointer;
            background-color: #d4a556; /* Color similar to the image */
            color: white;
            border-radius: 5px;
            font-size: 16px;
        }
        .custom-file-upload input[type="file"] {
            display: none;
        }
</style>