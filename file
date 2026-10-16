// Load your secret environment variables
require('dotenv').config();

// Access a variable (like a custom app name or server port)
const appName = process.env.APP_NAME || "Mobile Git Project";
const port = process.env.PORT || 3000;

console.log(`🚀 Success! Your start command is working.`);
console.log(`📱 Running "${appName}" on port ${port}...`);

// If you have a secret key saved, it will print here securely
if (process.env.SECRET_KEY) {
  console.log("🔒 Secret API Key loaded successfully!");
} else {
  console.log("⚠️ No secret key found in your .env file.");
}
