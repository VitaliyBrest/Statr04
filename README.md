# Statr04

const newPost = (post, addedAt = Date()) => ({
    ...post,
    addedAt,
})
const firstPost = {
    id: 1,
    author: 'vitaliy',
    }

    console.log (newPost(firstPost))
