 from fastapi.middleware.cors import CORSMiddleware
app.add_middleware(
    CORSMiddleware,
    allow_origins=["*"],        # in prod replace "*" with allowed origins
    allow_credentials=True,
    allow_methods=["*"],
    allow_headers=["*"],
)
