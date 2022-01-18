FROM node:alpine

WORKDIR /app

COPY ./package.json ./

RUN npm i

COPY . ./

ENV MONGODB_URL=mongodb+srv://selva21:footballislife@zomato-master.xmu4d.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
ENV GOOGLE_CLIENT_ID=578330019053-a4vg4k52ure5hi99oe581cif7fecpddt.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET=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
ENV AWS_S3_ACCESSS_KEY=AKIATNMBFYGVW6SCUZOU
ENV AWS_S3_SECRET_KEY=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
ENV NODE_ENV=production
ENV PORT=5000

# RUN npm run build

CMD ["npm", "run", "start"]