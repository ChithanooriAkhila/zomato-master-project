FROM node:alpine

WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . .


ENV MONGO_URL=mongodb+srv://Akhila13:Akhila@123@zomato-master.npbvy.mongodb.net/zomato?retryWrites=true&w=majority
ENV GOOGLE_CLIENT_ID=910076375561-vsculv5dnrpkuh8uvk1773fl9ok6o613.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET=SZsP_KoEMUbQGcwijD3127QJ
ENV AWS_S3_ACCESS_KEY=AKIA2G4RARAPZOQ3EM2Y
ENV AWS_S3_SECRET_KEY=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
ENV MAILGUN__DOMAIN=sandbox9f4d83f9560f4a71aec59011eb4a9948.mailgun.org
ENV MAILGUN__API__KEY=3d2c87739cfa7b9b0db054cdf6d60ea7-9776af14-eafee2c6
ENV RZR_PAY_ID=rzp_test_Mtb3kDcBe6fjhg
ENV RZR_PAY_SECRET=y9vUtGgAyiiPgmTnoTre0Cmu
ENV NODE_ENV=production
ENV PORT=4000

RUN npm run build


CMD ["npm", "run", "start"]