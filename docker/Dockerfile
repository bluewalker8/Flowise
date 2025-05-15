# ---------- Flowise (latest full build) ----------
FROM ghcr.io/flowiseai/flowise:latest

# Path where Flowise stores its SQLite DB.
# Keep identical to your Render persistent-disk mount.
ENV FLOWISE_DATA_PATH=/root/.flowise

# Expose the default port
EXPOSE 3000

# Start Flowise
CMD ["flowise", "start"]
