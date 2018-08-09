class DbCli < Formula
  desc "A CLI for interacting with database"
  homepage "https://github.com/moshloop/db-cli"
  url "https://github.com/moshloop/db-cli/releases/download/1.2/db-cli.zip"
  version "1.2"
  sha256 "b00ccaa80b3ec5a5f3d162d539242e0d92504c9718f4ae1cd0addfb0d67c140a"

  def install
    mv "db-cli_osx", "db-cli"
    rm "db-cli.exe"
    bin.install Dir["db-cli"]
  end
end
